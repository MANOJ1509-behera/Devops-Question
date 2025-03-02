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

## set - 4

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
set - 5
```
1. were you able to write some code as well in Jenkins (asking that I am able to write the Jenkins pipeline).
2. have you worked on AWS?
3. let's say I have a single page application.
Do you know how to post it in the S3 bucket?
4. let's say  that you have a S3 bucket.
Within that, I just have to make one of the folder or object as a public or can be accessed by external user.
What would you do?
5. if you want to restrict running of some   instances during weekends
and holidays.
How would you do?
6. Have you used event bridges?
7. Have you done any provisioning using MongoDB at last with Terraform?
8. how do you structure a Terraform project and how do you handle different environments?
9. Do you know something called the statefiles in Terraform?
10. can you speak about what are the backends available for state storage?
What are some of the best ones? and why?
11. Was it also used a lock with DynamoDB? and why?
12. if I use this Terraform refresh, what really happens?
13. there is a database which is auto-operating its migration version.
Okay. And we see it just over a month.
Okay.
How will you handle this situation?
14. Do you know what is the purpose of Terraform import command and when can we use it?
15. let's say we have an EC2 instance, which cannot be created without creating a VPC. How do you ensure that Terraform creates VPC first, before EC2?
16. how do you optimize the Docker image?
17. one last question is about, you know, deployment strategies.
Like, if there's going to be a rolling update, how we do it, you know?
18. Let's say you have a container crash.
Like how do you debug the crash in container?
19. For somebody who don't know Grafana and GLK, what will you describe these solutions as?

```
## set-6
```

1. Can you explain how Terraform works and describe its main components (providers, modules, state files)?
2. Explain the concept of "Infrastructure as Code" (IaC) and why it's important in DevOps.
3. How do you manage Terraform state files in a team environment?
4. How would you handle versioning of Terraform configurations?
5. How do you handle secret management in Terraform ?
6. What is ENI.
7. What are the different compute classes available for ec2 and how do they differ.
8. Cloudfront vs Global Accelarator?
9. What is gateway load balancer?
10. How would you set up a high-availability architecture in AWS?
11. Can you explain AWS IAM roles and policies and how to manage them securely for a DevOps pipeline?
12. What is Ansible, and how does it differ from other configuration management tools like Chef or Puppet?
13. How do you use Ansible to automate infrastructure provisioning and application deployment?
14. Sample playbook to install nginx where OS is CentOS
15. Are Ansible playbooks Idempotent ?
16. Multistage docker build ?
17. Are docker images immutable ?
18. Where are docker volumes stored?
19. What is docker compose ?
20. Can you explain the architecture of Kubernetes and describe its key components (Pods, Nodes, Services, etc.)?
21. What is the difference between a Deployment and a StatefulSet in Kubernetes?
22. How do you manage scaling and resource requests/limits in Kubernetes?
23. How would you troubleshoot a pod that is failing to start in Kubernetes?
24. Explain how you would implement continuous deployment in Kubernetes. What tools or approaches would you use?
25. What monitoring tools have you worked with, and how do you integrate them into your DevOps workflow?
26. How would you set up monitoring for a microservices architecture running on Kubernetes?
27. How do you ensure high availability for monitoring and logging systems?
28. Explain how you would set up Prometheus and Grafana for application monitoring and alerting.
29. What metrics are most important for monitoring cloud infrastructure, and why?
30. Explain how you would write a script to monitor disk space usage on an EC2 instance and send an alert if the usage exceeds a threshold.

```
## Set-6

```
🤖 What do you know about DevOps?
💼 What types of projects have you worked on? Can you please explain?
🛠️ What tools have you integrated into DevOps?
🌐 I have a VPN in the organization and we use AWS Cloud. If a new employee joins, how can I create a user in AWS and grant them access through the VPN?
💻 Explain the steps or implementation. Senior, take your time—I’ll access and use my laptop.
🧐 I have an EC2 instance that’s already created. How would you find out who created it?
🧑💻 What is metadata in EC2?
🔍 I’ll show you some services in my AWS account. Can you identify any security leaks in the infrastructure?
⚠️ What happens when a GitLab CI/CD runner fails?
🔄 If the GitLab runner fails, will it impact production?
⛔ If the GitLab server goes down, what would you do to regain access to the code and bring it back up?
🔒 How would you secure the GitLab server?

🗂️ What files need to be backed up in GitLab to ensure recovery of the code?
It was a great opportunity to engage in a thoughtful discussion about DevOps practices, AWS, and security. I am looking forward to applying these insights to my next challenge!

```

## set - 7

```
1. were you able to write some code as well in Jenkins (asking that I am able to write the Jenkins pipeline).
2. have you worked on AWS?
3. let's say I have a single page application.
Do you know how to post it in the S3 bucket?
4. let's say that you have a S3 bucket.
Within that, I just have to make one of the folder or object as a public or can be accessed by external user.
What would you do?
5. if you want to restrict running of some instances during weekends
and holidays.
How would you do?
6. Have you used event bridges?
7. Have you done any provisioning using MongoDB at last with Terraform?
8. how do you structure a Terraform project and how do you handle different environments?
9. Do you know something called the statefiles in Terraform?
10. can you speak about what are the backends available for state storage?
What are some of the best ones? and why?
11. Was it also used a lock with DynamoDB? and why?
12. if I use this Terraform refresh, what really happens?
13. there is a database which is auto-operating its migration version.
Okay. And we see it just over a month.
Okay.
How will you handle this situation?
14. Do you know what is the purpose of Terraform import command and when can we use it?
15. let's say we have an EC2 instance, which cannot be created without creating a VPC. How do you ensure that Terraform creates VPC first, before EC2?
16. how do you optimize the Docker image?
17. one last question is about, you know, deployment strategies.
Like, if there's going to be a rolling update, how we do it, you know?
18. Let's say you have a container crash.
Like how do you debug the crash in container?
19. For somebody who don't know Grafana and GLK, what will you describe these solutions as?


```

## set-7
```
𝐋𝐢𝐧𝐮𝐱:
What is the command to check system uptime?
How do you create and delete users in Linux?
What is the difference between hard links and soft links?
How do you check disk space usage?
What is the purpose of the chmod and chown commands?
How do you check active processes on a system?

𝐆𝐢𝐭:
What is Git, and why is it used in DevOps?
What is the difference between git fetch and git pull?
How do you resolve a merge conflict in Git?
Explain branching strategies in Git.
What is the purpose of the .gitignore file?

𝐃𝐨𝐜𝐤𝐞𝐫:
What is Docker, and how does it work?
What is the difference between an image and a container?
How do you create a Dockerfile, and what are common instructions?
Explain Docker Compose and its use cases.
What is the purpose of Docker volumes?

𝐉𝐞𝐧𝐤𝐢𝐧𝐬 (𝐂𝐈/𝐂𝐃):
What is CI/CD, and why is it essential in DevOps?
How do you configure a Jenkins pipeline?
What is the difference between a declarative and a scripted pipeline?
How do you integrate Jenkins with Git?
Explain how to manage Jenkins plugins and upgrades.

𝐓𝐞𝐫𝐫𝐚𝐟𝐨𝐫𝐦:
What is Terraform, and why is it used in DevOps?
Explain the Terraform workflow (init, plan, apply, destroy).
What is the purpose of state files in Terraform?
How do you manage remote backends in Terraform?
What is the difference between count and for_each?

𝐊𝐮𝐛𝐞𝐫𝐧𝐞𝐭𝐞𝐬:
What is Kubernetes, and why is it popular?
Explain the difference between Pods, ReplicaSets, and Deployments.
What is a ConfigMap, and how is it used?
How do rolling updates work in Kubernetes?
What is the role of etcd in Kubernetes?

𝐀𝐖𝐒 𝐁𝐚𝐬𝐢𝐜𝐬:
What is AWS, and what are its primary services?
What is the difference between EC2, S3, and RDS?
Explain vertical vs. horizontal scaling in AWS.
What is a security group, and how does it differ from a network ACL?
What is the purpose of AWS IAM roles and policies?
These questions are tailored to entry-level DevOps roles and will help you showcase your understanding of core concepts and tools.



```
## set - 8
```
🔧 Real-Time DevOps Challenge & Solution 🚀

🎯 Problem:
While deploying a new microservices architecture, one of the services kept failing intermittently. The logs showed vague "connection timeout" errors, but everything seemed fine on the surface – the database was up, the network stable, and other services were running without issues.
This delay in identifying the root cause led to missed SLAs and a frustrated team.

🧠 Root Cause Analysis:
After digging deeper, it turned out that:
The Kubernetes liveness probes were misconfigured, causing the service to restart before a healthy connection could be established.
The database connection pool was exhausted due to high concurrent requests during peak load, which was not anticipated in the testing environment.

🔧 Solution:
Updated the liveness and readiness probes to account for a proper initialization period by increasing initialDelaySeconds.
Increased the database connection pool size and implemented circuit breaker patterns to handle peaks gracefully.
Set up a load testing pipeline to simulate real-world peak traffic conditions in pre-production environments.

```

## Set - 9

```
🔵 1. What is IAM service in AWS (IAM Group, IAM Role, IAM Policies, Trusted Policies)?
🟢 2. What is a VPC, Subnet (Private and Public), Availability Zones, and Region? How do we configure a network inside a VPC?
🟡 3. How would you design a fully elastic, scalable, and resilient architecture for an application with security optimizations implemented?
🟠 4. Explain CloudFront Distribution Network (CDN) and how it works.
🔴 5. How does an S3 website work with CloudFront, and how do we restrict direct S3 URL access while allowing only domain-based access? Also, how do we configure SSL certificates for secure domain entry?
🔵 6. Explain the CI/CD pipeline, its stages, and why it is essential.
🟢 7. Suppose I have three stages: Checkout, Build, and Deploy, and this pipeline runs 4000 times a day. How would you optimize it?
🟡 8. What is the difference between Dockerfile, Docker Image, and Docker Container?
🟠 9. What is a multi-stage build, how would you optimize a Dockerfile, and why is it important?
🔴 10. What is container orchestration, and how do we manage it?
🔵 11. Explain the architecture of Kubernetes, its core components, and its supplementary entities.
🟢 12. Explain the workflow of a Kubernetes cluster and how instructions flow through the entire system.
🟡 13. What are the most common errors in a Kubernetes cluster, and how do we troubleshoot them?
🟠 14. What is an Ingress, why do we need it, and are there any alternatives other than Ingress?

✅ 𝙎͟𝙘͟𝙚͟𝙣͟𝙖͟𝙧͟𝙞͟𝙤͟-͟𝘽͟𝙖͟𝙨͟𝙚͟𝙙͟ ͟𝙌͟𝙪͟𝙚͟𝙨͟𝙩͟𝙞͟𝙤͟𝙣͟𝙨͟
📌 Your team is facing slow build times in Jenkins. How would you optimize the pipeline for faster execution?
📌 A production deployment failed midway. How do you troubleshoot and roll back changes while minimizing downtime?
📌 You have been asked to migrate an on-prem application to the cloud. What factors will you consider for the migration?
📌 Your Kubernetes cluster is experiencing high CPU usage. How do you investigate and resolve this?
📌 A security audit found vulnerabilities in your containerized environment. What steps would you take to secure it?


```


## set-10

```
1. Introduction current project and roles and responsibilities
2.What is CI-CD
3. What is Yaml file and how did you use in Ansible
4. What is difference between Ansible and Puppet?
5.What is the call back plugins in Ansible?
6. Maven Architecture Explain?
7.How do You check maven version? What is maven Artifacts?
8.Why are Maven plugins are used?
9. What is the maven order of inheritance?
10.what is meant by term dependencies and repository in maven?
11. what happen if the dependencies are not accepting in local repositories? what maven do?
12. what is the snapshot in maven?
13. What is the build profile?
14. Kubernetes Architecture?
15.What do you know docker? and docker container?
16. How does docker differ to VM?
17. How do you create docker container?
18.Difference between docker Run and docker start?
19. What is the purpose of docker compose for this are you write yaml individual or single Yaml file use for containers? What is docker swarm?
20. What is container orchestration?
21. What is the Pod in Kubernetes?
22. How do rolling updates useful in Deployment?
23. What is Name space in Kubernetes?
24.What is Daemon Sets? what is replica set?
25.What are the advantages of Kubernetes?
26. How does Kubernetes handle security and access?
27.What is the Jenkins uses?
28. what is the pol SCM uses in Jenkins?
29. what are the build triggers in Jenkins?
30. what is the language in ci-cd pipeline?
31. what are key components in Master slave configuration?
32. What is pipeline in Jenkins?
33. what is global tool configuration?
34. How do integrate Jenkins with AWS?
35. What is RBAC and how do configure RBAC in Jenkins ?
36. can you explain build life cycle in Jenkins?
37. What is shared libraries in Jenkins?
38. Difference between Jenkins pipeline AWS code pipeline?
39. What is the broken pipeline in Jenkins? how can you trouble shoot?
40. What is DevOps?
41. What is Elastic Load Balancer?
42. Describe the troubleshoot time when you have product issues?
43.What are the monitoring Tool have you use?
44. Have worked on resolving production issue? 


```
## set-11

```

### **1. Core DevOps Concepts**
- **What is CI/CD, and how do you implement it in a real-world scenario?**
- **Explain the difference between Infrastructure as Code (IaC) and Configuration Management. Can you name tools for each?**
- **How do you handle rollbacks in a deployment pipeline?**

---

### **2. Cloud-Native and Kubernetes**
- **How do you manage multi-cluster Kubernetes environments?**
- **What are the key challenges of running stateful applications on Kubernetes, and how do you address them?**
- **Can you explain the role of a service mesh in a microservices architecture?**

---

### **3. Security in DevOps (DevSecOps)**
- **How do you integrate security into a CI/CD pipeline?**
- **What tools do you use for vulnerability scanning and compliance checks?**
- **Explain the concept of "shift-left security" and how you’ve implemented it.**

---

### **4. Automation and Scripting**
- **Write a script to automate the deployment of a containerized application to a Kubernetes cluster.**
- **How do you automate infrastructure provisioning using Terraform or Pulumi?**
- **What’s your approach to automating monitoring and alerting?**

---

### **5. Observability and Monitoring**
- **What metrics do you monitor to ensure the health of a production system?**
- **How do you implement distributed tracing in a microservices architecture?**
- **What’s the difference between logging, monitoring, and observability?**

---

### **6. Problem-Solving and Troubleshooting**
- **A production deployment has failed. Walk me through your troubleshooting process.**
- **How do you handle a situation where a critical vulnerability is discovered in a live application?**
- **What steps would you take to optimize a slow CI/CD pipeline?**

---

### **7. Collaboration and Culture**
- **How do you ensure effective collaboration between development, operations, and security teams?**
- **Describe a time when you had to resolve a conflict between teams during a deployment.**
- **How do you stay updated with the latest DevOps trends and tools?**

---

### **8. Future-Readiness**
- **How do you see AI and machine learning impacting DevOps in the next 2-3 years?**
- **What’s your take on Green DevOps, and how would you implement sustainable practices?**
- **How do you approach learning new tools and technologies in a fast-evolving field like DevOps?**

````

## set -12

```
1. Can you write a real time python automation code.
2. Explain Jenkins Master/Slave architecture
3. What is liveness probe and readiness probe
4. What are the parameters needed to deploy an application into Kubernetes using pipeline.
5. What is State file in terraform and explain the lock process.
6. where you store the sensitive information
7. What is the issue you are facing at the time of building an image.
8. How to stop direct commits to GitHub.
9. Kubernetes YAML files.
10. What is Tag in Git.
11. where do you deploy an application in Kubernetes.
12. How to set the build is scheduled to particular node in Jenkins. 
13. What is the real time issue you are facing when building a java package using maven.
14. Where you used python and shell scripting
15. How many builds are stored in a pipeline project of Jenkins.


```
