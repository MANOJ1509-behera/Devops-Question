# Devops-Question
```
1. You are tasked with securing a Linux server that hosts a web application. The server is currently exposed to the internet and has a weak root password. Describe the steps you would take to secure the server.
2. One of your team members accidentally ran a command that corrupted the file system on a critical Linux server. The server is no longer booting, and you need to recover the data. Walk me through the steps you would take to recover the file system.
3. Your team uses a backup script to download the latest backup file from a remote server. However, the script is currently not working due to changes in the remote server's configuration. Write a script that downloads the latest backup file from the remote server using SSH.
4. You are using Terraform to manage your infrastructure, and you notice that one of your resources is not being updated correctly. Describe how you would use Terraform's taint and untaint commands to resolve the issue. Additionally, explain the difference between stateful and stateless resources in Terraform.
5. Your team is using Jenkins for continuous integration and continuous deployment (CI/CD). Describe the master-slave architecture of Jenkins and how it enables distributed builds and deployments.
6. You are tasked with implementing a CI/CD pipeline from scratch for a web application. Describe the steps you would take to implement the pipeline, including how you would ensure zero downtime deployments and implement rollbacks.
7.Explain the concept of shift-left in DevOps and how it enables teams to detect and fix issues earlier in the development cycle.
8.What is the difference between the ADD and COPY instructions in a Dockerfile?
9.You accidentally committed sensitive information to a Git repository. Describe the steps you would take to remove the sensitive information from the repository's history.
10.One of your team members accidentally deleted a critical branch in a Git repository. Describe the steps you would take to recover the deleted branch.
11. Explain the difference between the origin and upstream remotes in a Git repository.
12. Describe the lifecycle of a Docker container, including how it is created, started, stopped, and deleted.
13. Explain the concept of a ReplicaSet in Kubernetes and how it ensures that a specified number of replicas of a pod are running at any given time
14. Describe how to configure a NAT gateway in AWS to enable outbound internet access for instances in a private subnet.
15. What happens when you delete the /var/lib/docker/overlay directory on a Docker host
16. Is it possible to run a virtual machine (VM) in AWS without creating an EC2 instance? If so, how
17. Explain the difference between stopping and terminating an EC2 instance. Additionally, describe the concept of EC2 hibernation and how it enables instances to be restarted from a saved state.
```
## Day - 2
```
1. Your company is planning to migrate its on-premises data center to AWS. As part of the migration strategy, you need to ensure minimal downtime and data loss. How would you plan and execute the migration process?

2. Can you describe a situation where you used Docker to solve a specific problem?

3. You're in charge of maintaining Docker environments in your company and You've noticed many stopped containers and unused networks taking up space. Describe how you would clean up these resources effectively to optimize the Docker environment.

4. You're part of a development team deploying a microservices architecture using Docker containers. One of the containers, critical to the system's functionality, has suddenly started failing without clear error messages. How do you debug issues in a failing Docker container?

5. You are managing a high-traffic web application hosted on AWS. Recently, you've noticed intermittent performance issues during peak hours, resulting in increased latency and occasional downtime. How would you diagnose and address this issue?

6. You are responsible for securing an AWS infrastructure hosting sensitive customer data. How would you design and implement a robust security strategy to protect against data breaches and unauthorized access?

7. Your organization is experiencing exponential growth in data volume, leading to increased storage costs on AWS. How would you design a cost-effective storage solution that balances performance, scalability, and cost efficiency?

8. How do you set up a Kubernetes cluster on GKE? 

9. What are some strategies for scaling Kubernetes applications on GKE? 

10. Explain the role of Helm in Kubernetes deployments.
 
11. How do you secure Kubernetes pods and services in GKE? 

12. What is the importance of resource quotas and limits in Kubernetes?

```
# Day-3
---------
```
1. What are your typical daily responsibilities in your current role?


2. Where is your current project hosted?


3. What AWS services have you worked with so far?


4. Do you have practical experience with AWS CloudFormation?


5. Are you more comfortable using CloudFormation or Terraform?


6. Have you worked with Prometheus and Grafana in your projects?


7. What tasks related to Prometheus are you currently handling?


8. Have you ever created a Dockerfile?


9. What CI/CD tools have you used in your projects?


10. Can you describe the process that occurs when a developer commits code or creates a pull request?


11. Where do you usually execute your Dockerfiles?


12. What is the difference between a Docker image and a container?


13. If you have a 5GB Docker image but need to deploy it on an EC2 instance with only 2GB of RAM, how would you address this?


14. When working with Terraform, do you generally create modules or scripts?


15. What types of Terraform blocks have you written?


16. Can you explain the different Terraform blocks you’ve used?


17. Why would you use a dynamic block in Terraform?


18. What is the difference between a dynamic block and an output block in Terraform?


19. How many environments are you managing?


20. Does each environment have its own Kubernetes cluster?


21. How many nodes are there in your Kubernetes clusters?


22. What are the specifications for the nodes in your Kubernetes clusters?


23. How many pods are currently running in your clusters?


24. Are pods allocated to specific nodes?


25. If not, why is it still referred to as a cluster?


26. What types of services are you utilizing in Kubernetes?


27. Are Kubernetes services exposed to the outside world?


28. Have you worked with an Ingress controller in your projects?


29. When writing Kubernetes YAML files, do you specify the kind as Pod, ReplicaSet, or Deployment?


30. Why would you use kind: Pod, kind: ReplicaSet, and kind: Deployment in separate YAML files when it seems possible to use only kind: Deployment?


31. Why are Kubernetes resources like Pod, ReplicaSet, and Deployment defined separately when a Deployment can manage both Pods and ReplicaSets?


32. What is your reason for seeking a change in your current role?

```

set - 4

```
1. what tools do you use on a daily basis from the Linux perspective?
2. What are inodes in Linux?
3. any experience with, RAID configurations?
4. Any experience with Docker?
5. network connectivity that you can utilize in an authorized environment for, you know, communication between, different containers?
6. Have you, created your own images for containers?What application was it?
7. what were the security considerations that you have, taken?
8. what's the difference between a stateful set and Daemon sets?
9. where or why you used Statefull set. How does it help? 
10. While creating a manifest file Mhmm. What are the 4 major, you know, points or things that you have to add in that manifest file.
11. how was the Jenkins environment that you're using? What considerations have you done while you're doing that?
12. What is, the default home directory for Jenkins for a master and for a slave?
13. Were you using the root user to run the agent part of Jenkins in the slave servers?
14. Have you worked on setting up, like, additional storage for your worker nodes in Kubernetes?
15. What have you done on the, Prometheus Grafana part?
16. How Kuber how Prometheus and Grafana or, like, how the logs or the monitoring would have been done in a Kubernetes cluster and how things were set up
17. what does it require that so that Prometheus gets this details?
18. Coming to, the Terraform, what was your role on that?
19. What modules have you worked on?
20. why was it required to create a custom module
21. What is git squash?
22. What is Gitstash? why is it used?
23. What are the different types of, disks that is available in, AWS?
24. How would you, like, ascertain, instance type when you have to deploy 1? What parameters would you, you know, take into consideration?
25. What  tools have you used to  backup?
26. Have you used s3?What  was the purpose for? and classes?
27.  what other AWS services have you used?
28. Have you used load balancing based on route 53?

```


