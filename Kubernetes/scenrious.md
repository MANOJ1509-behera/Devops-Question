```
Kubernetes Real Time Scenarios Part 1

Scenario 1

How do you ensure a zero-downtime deployment for multiple services in a production environment?

Resolution:

 Achieving zero-downtime deployments requires careful use of rolling updates, readiness probes, and traffic routing. Here’s how you can implement it:

Rolling Update: Use rolling updates with a small increment in replicas to ensure that only a portion of the pods are updated at a time, reducing the risk of downtime:

```
apiVersion: apps/v1 
kind: Deployment 
metadata: 
 name: multi-service-deployment 
spec: 
 replicas: 4 
 strategy: 
 type: RollingUpdate 
 rollingUpdate: 
 maxUnavailable: 1 
 maxSurge: 1
```

Readiness Probes: Define readiness probes to ensure that the new pod version is ready to serve traffic before it’s added to the load balancer:

```
readinessProbe:
 httpGet:
 path: /health
 port: 8080
 initialDelaySeconds: 10
 periodSeconds: 5
```

Traffic Routing: Use an Ingress or Istio Gateway to route traffic based on header/cookie values for canary testing:

```
apiVersion: https://lnkd.in/gfWk7kfm
kind: VirtualService
metadata:
 name: multi-service-route
spec:
 hosts:
 - multi-service.example.com
 http:
 - route:
 - destination:
 host: multi-service
 subset: v2 
 weight: 10
 - destination:
 host: multi-service
 subset: v1
 weight: 90
```

Scenario 2

How do you implement a blue-green deployment strategy with an easy rollback option?

Resolution:
 In a blue-green deployment, two identical environments (blue and green) are maintained. Traffic is shifted between them without downtime, allowing easy rollbacks.

Create Two Deployments (blue and green): Define two separate deployments for the blue and green environments.

```
apiVersion: apps/v1
kind: Deployment
metadata:
 name: myapp-blue
spec:
 replicas: 5
 template:
 spec:
 containers:
 - name: myapp-container
 image: myapp:v1
```

Update the Ingress: Modify the Ingress (or Istio Gateway) to point to the green deployment when ready:

```
apiVersion: networking.k8s.io/v1
kind: Ingress
metadata:
 name: myapp-ingress
spec:
 rules:
 - host: myapp.example.com
 http:
 paths:
 - backend:
 serviceName: myapp-green
 servicePort: 80
```

Rolling Back: If the green deployment has issues, switch back to blue by modifying the Ingress to point to myapp-blue again. This ensures that users always hit a stable environment.
```
