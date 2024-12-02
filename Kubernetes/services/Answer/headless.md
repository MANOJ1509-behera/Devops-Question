
### 1. What are Headless Services in Kubernetes?
```
Every K8s service performs load-balancing of requests.

When your app performs a DNS lookup for a service, it returns its cluster IP, so your request gets forwarded to one of the pods. This is great for the usual stateless services.

But imagine that your app needs to connect to ALL the pods in the service. How do you achieve this? 🤔

Enter Headless Service!

A headless service removes cluster IP from the equation and simply returns all pods' IPs upon DNS lookup.
Your app can then choose whether to connect to all or a subset of those IPs.

You make a service headless by simply setting “clusterIP: None” in your service configuration


Some use cases of Headless Service:
1. Stateful services: like databases, where you need separate writer & readers endpoints.
2. Custom health check probes
3. Jenkins server wanting to connect to all its worker nodes

```

![1730184686657](https://github.com/user-attachments/assets/204dc4a5-841d-4ee6-a095-84b3dbc2c400)
