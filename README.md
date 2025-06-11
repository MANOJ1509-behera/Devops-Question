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

## set - 12

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

## set - 13

```
1.Can you walk us through your experience as a DevOps Engineer? 
2.What has been your biggest challenge in DevOps, and how did you handle it? 3.What DevOps tools have you used for CI/CD pipeline automation? Can you describe how you set up a pipeline? 
4.Have you worked with GitOps? Can you explain how it differs from traditional CI/CD? 
5.How do you manage pipeline security and ensure compliance with DevSecOps best practices? 
6.Have you used GitHub Actions? Can you describe a complex automation workflow you implemented? 
7.How do you deploy and manage Kubernetes clusters in a production environment?
 8.What challenges have you faced with Kubernetes deployments, and how did you troubleshoot them? 
9.How do you handle Docker container security in a DevOps pipeline? 
10.Can you explain the use of ArgoCD or Flux in an automated deployment setup?
11.Can you explain how you automate infrastructure provisioning using Terraform or Ansible?
12.How do you ensure IaC scripts remain maintainable and do not introduce vulnerabilities?
13.What experience do you have with AWS cloud technologies?
14.How do you manage multi-cloud (AWS & Azure) deployments effectively?
15.How do you optimize cloud costs while ensuring performance?
16.Have you developed applications using Java or Quarkus?
17.Can you explain the differences between RESTful APIs and GraphQL?
18.How do you handle authentication and security in API development?
19.What best practices do you follow for PostgreSQL database performance tuning?
20.Can you describe a critical production issue you encountered and how you resolved it?
21.How do you handle Incident Management (IM) and Critical Incident Management (CIM)?
22.What strategies do you use to reduce system downtime?
23.How do you approach Problem Management (PM) and Change Management (CM)?
24.What are the best practices you follow for securing applications and cloud infrastructure?
25.Have you worked with ITIL operation processes (Incident, Problem, Change management)?
26.How do you ensure compliance with industry security standards?
27.How do you integrate security scanning in CI/CD pipelines?
28.Have you worked in an Agile environment? How do you handle rapid changes in requirements?
29.How do you balance technical priorities vs. business needs?
30.How do you manage cross-functional collaboration in a DevOps team?
31.How do you handle conflict resolution within a team?
32.Have you worked with microservices architecture? How do you manage service communication and security?
33.Do you have experience with Nagios or other monitoring tools?
34.Can you describe a time when you had to mediate a dispute between team members?

```

## set - 14

```
1. Introduction and Day to Day activities 
2. In Your Company You worked in Terraform there you have maintain statefiles. How to secure it in remote in AWS How you lock the files by using Dynamo DB.
3. Who will take it create dynamo DB for likes means you only take decision or some bady give insteuctions.
4 How can deploy the application by using ECS forgate and EKS.
5. How can open forgate in ECS for EKS Cluster.
6 Are deploy applications on EKS are creating infrastructure only.
7.How to auto play books in yaml. How can you create and run multiple tasks play book.
8. what is role of Ansible in monitoring explain detail way.
9. In Sonarqube will find vulnerabilities how to you find it explai in detain.
10. Tell me difference between CMD and Entry point.
11. In your organization do you face any errors . are trouble shoot your own without taking any one help.
12. how can create and check the Kubernetes cluster.
13. How can you monitor the Kubernetes logs
14. which monitoring tool you use like graphana or Prometheus. where you install it like your local machine or Ec2 or Kubernetes cluster.
15. If you install it in your ec2 how can communicate with kubernetes.
16.where you monitor the logs in prometheus.
17. Are You use Cloud Watch. Where the resource information is present. 
18.In cloud watch are you able to find how much memory consumed and rest directly. is it possible.
19. In GitHub unexpectedly lost rebate commits how can you revert back . is it possible to regain logs.
20. Difference between rebase and Merge.

```

## set-15

```
1. Introduction and Day to Day activities 
2. In Your Company You worked in Terraform there you have maintain statefiles. How to secure it in remote in AWS How you lock the files by using Dynamo DB.
3. Who will take it create dynamo DB for likes means you only take decision or some bady give insteuctions.
4 How can deploy the application by using ECS forgate and EKS.
5. How can open forgate in ECS for EKS Cluster.
6 Are deploy applications on EKS are creating infrastructure only.
7.How to auto play books in yaml. How can you create and run multiple tasks play book.
8. what is role of Ansible in monitoring explain detail way.
9. In Sonarqube will find vulnerabilities how to you find it explai in detain.
10. Tell me difference between CMD and Entry point.
11. In your organization do you face any errors . are trouble shoot your own without taking any one help.
12. how can create and check the Kubernetes cluster.
13. How can you monitor the Kubernetes logs
14. which monitoring tool you use like graphana or Prometheus. where you install it like your local machine or Ec2 or Kubernetes cluster.
15. If you install it in your ec2 how can communicate with kubernetes.
16.where you monitor the logs in prometheus.
17. Are You use Cloud Watch. Where the resource information is present. 
18.In cloud watch are you able to find how much memory consumed and rest directly. is it possible.
19. In GitHub unexpectedly lost rebate commits how can you revert back . is it possible to regain logs.
20. Difference between rebase and Merge.

```

## set- - 16

```
🔹 Ansible & Automation
1. What are some routine tasks you have automated using Ansible playbooks?
🔹 CI/CD & Security
2. Have you used SonarQube and Trivy in your CI/CD pipeline? How did you share the reports with the DevOps team?
3. How did you optimize CI/CD to reduce deployment time by X%?
4. What agent did you use for running builds in your CI/CD pipeline? Do you remember the agent container names?
🔹 AWS Cost Optimization & Networking
5. You reduced AWS costs by X%—how did you analyze resource allocation and optimize costs?
6. What are the downsides of using a single Ingress controller instead of multiple load balancers?
7. What happens if there’s a traffic spike for one service?
🔹 AWS Services & Infrastructure
8. What AWS services have you worked with?
9. What’s the difference between NACL and Security Groups?
10. How do S3 and EBS differ?
11. Is S3 region-dependent?
12. What is an Availability Zone?
🔹 Kubernetes & Docker
13. How do you determine resource limits for your Kubernetes cluster?
14. What steps can you take to reduce the size of a Docker image?
15. What are the pros and cons of using Alpine images?
🔹 Terraform & Infrastructure as Code
16. Why is the Terraform state file important?
17. If an EC2 instance already exists and you write the same Terraform configuration, what happens when you run Terraform commands?
18. How do you import manually created AWS resources into Terraform?
19. Why should we run terraform plan before terraform apply?
20. What happens if cloud infrastructure changes between terraform plan and terraform apply?
21. What key resources are required in Terraform for deploying a fully functional production-grade EC2 instance?
🔹 DevOps Best Practices
22. If you’re given a new project with no CI/CD pipeline, how would you design and implement one?
23. How does Argo CD detect when an image is updated?
24. How do you connect to an EC2 instance after deployment?

```

## set - 17

```
1.What is Kubernetes and what does it do? 
2.List the main components of Kubernetes architecture 
3.You have an application deployed on Kubernetes that is experiencing increased traffic. How would you scale the application to handle the increased load? 
4.While troubleshooting a networking issue in the cluster, you noticed kube-proxy in the logs. What is the role of kube-proxy in Cluster? 
5.Your team is planning a high-availability Kubernetes cluster. Describe the Process and Considerations for Designing a High-Availability Kubernetes Cluster. 
6.In your Kubernetes environment, a master or worker node suddenly fails. What happens when the master or the worker node fails? 
7.How does ingress help in Kubernetes? 
8.You're selecting a service to expose your application hosted on Kubernetes. List the different types of services in Kubernetes. 
9.What do you know about Headless service? 
10.Your manager has instructed you to run several scripts before starting the main application in your Kubernetes pod, and suggested using init containers. What is the init container? 
11.A Critical application running on one of nodes is not working properly. How do you monitor applications in Kubernetes? 
12.Your manager read an article on GitOps and want you to do POC on it. What is GitOps and How do you implement it? 
13.Company is very concerned about Securing Clusters. List some security measures that you can take while using Kubernetes. 
14.Explain Kubernetes RBAC. 
15.How do you perform maintenance on the K8 node? 
16.Explain DaemonSets. 
17.A Junior Engineer working with Database on K8s is confused and asks you to Differentiate between ConfigMaps and Secret? 
18.What is the purpose of Operators? 
19.How can you run a pod on a specific node? 
20.Suppose a pod exceeds its memory limit. What signal will be sent to the process? 
21.You need to ensure that a specific pod remains operational at all times. How to make sure that pod is always running? 
22.What you will do to upgrade a Kubernetes cluster? 23.Why should we use custom namespaces ? 
24.Can you schedule the pods to the node if the node is tainted?

```

## set - 18

```


1. A user ssh into a server yesterday. But today not why?
2. How to make the deployed application on EC2 instances to be access from end users.
3. How many types of scaling in AWS.
4. I want to allow only requests from the particular region. How?
5. The application is not receiving the request. What are the possible ways to troubleshoot.
6. Is there any auto scaling in Kubernetes and how it works.
7. Where the private keys available in Linux server.
8. Can you explain the whole process of VPC and components.
9. In monitoring dashboard, it shows the one of the pods is not running. How to trouble shoot it.
10. How Grafana took the metrics to visualize on dashboards.

```

## set - 19

```
 1. What is the difference between Docker and Kubernetes?
 2. How does Terraform manage infrastructure state?
 3. Explain the concept of Blue/Green Deployment.
 4. How do you ensure zero-downtime deployments in Jenkins pipelines?
 5. Describe the purpose of Helm in Kubernetes.
 6. What is the significance of Infrastructure as Code (IaC) in cloud environments?
 7. How do you handle secrets management in Ansible?
 8. Explain Canary Deployment and its benefits.
 9. How would you troubleshoot a failing pod in Kubernetes?
 10. What are the best practices for scaling a microservices architecture in AWS?
 11. How do you implement CI/CD pipelines using Jenkins and Git?
 12. What is the role of AWS CodePipeline in CI/CD?
 13. Explain the difference between Stateful and Stateless applications in Kubernetes.
 14. How do you monitor and log containers using the ELK stack?
 15. What is the purpose of AWS CloudFormation and how does it work?
 16. How do you manage container networking in Docker?
 17. Explain the concept of GitOps and its benefits.
 18. How do you implement auto-scaling in Kubernetes clusters?
 19. What is the difference between a Docker Image and a Docker Container?
 20. How do you optimize the performance of a Jenkins pipeline?

```

## set - 20

```
1. What is DevOps, and why is it important? 
2. How does DevOps differ from Agile and traditional IT operations?
3. What are the key benefits of DevOps? 
4. What are some key DevOps tools you have worked with?
5. Explain the DevOps lifecycle. 
6. What are some common Linux commands used in DevOps? 
7. How do you schedule a cron job in Linux? 
8. What is the difference between grep, sed, and awk? 
9. How do you check system performance in Linux? 
10.How would you write a Bash script to automate a task? 
11.What is Git, and why is it used in DevOps? 
12.Explain the difference between Git merge and Git rebase. 
13.What is a Git branching strategy? 
14.How do you resolve merge conflicts in Git? 
15.Explain the purpose of a Git commit, push, pull, and fetch.
16.What is Continuous Integration (CI), and why is it important? 
17.What is Continuous Deployment (CD), and how does it differ from Continuous Delivery? 
18.How would you set up a CI/CD pipeline? 
19.What are some common CI/CD tools, and how do they compare? 
20.How do you handle rollback in a CI/CD pipeline? 
 21.What are the benefits of cloud computing in DevOps? 
22.What are the main services provided by AWS for DevOps?
23.What is the difference between EC2, ECS, and EKS in AWS?
24.What is IAM, and how does it help in security? 
25.How would you deploy an application in the cloud? 
26.What is Docker, and how does it work? 
27.Explain the difference between a Docker image and a Docker container. 28.What is Kubernetes, and why is it used? 
29.What is a Kubernetes Pod, and how does it work? 
30.What is the difference between a Deployment and a StatefulSet in Kubernetes? 
31.What is Infrastructure as Code (IaC), and why is it important? 
32.How does Terraform differ from Ansible? 
33.What are Terraform modules, and how do they work? 
34.Explain the difference between terraform plan and terraform apply. 
35.How would you manage secrets in Terraform? 
36.What is monitoring in DevOps, and why is it necessary? 
37.What is the difference between Prometheus and Grafana? 
38.How would you set up an alert in Prometheus? 
39.What is the ELK Stack, and what is it used for? 
40.How do you debug performance issues in a production system? 
41.What are some best practices for securing CI/CD pipelines? 
42.What tools do you use for security scanning in DevOps? 
43.How would you handle secrets management in DevOps? 
44.How do you ensure compliance with security policies in DevOps workflows?
45.How would you handle a failing deployment? 
46.What steps would you take if a Kubernetes pod is stuck in a crash loop? 
47.How do you troubleshoot high CPU usage in a cloud environment? 
48.How would you optimize a slow-running CI/CD pipeline? 
49.Tell me about a time when you solved a major DevOps challenge. 
50.What is HPA (Horizontal Pod Autoscaler)?


```
## set - 21

```
1. What is the role of IAM roles and policies?
2. Can you explain the Terraform plan and its purpose?
3. What is AWS Lambda, and how does it work?
4. How do you invoke a Lambda function, and where do you configure it?
5. Can you describe how Lambda handles scaling and event-based invocations?
6. What is Amazon CloudWatch, and have you configured any custom metrics?
7. What metrics are available on your CloudWatch dashboard?
8. How do you configure CPU utilization on your CloudWatch dashboard?
9. How do you attach an SSL certificate to an S3 bucket?
10. What type of encryption have you implemented in your project?
11. If an S3 bucket has a read-only policy, can you modify objects in the bucket?
12. Why did you choose Terraform over Boto3 for infrastructure provisioning?
13. What is a Content Delivery Network (CDN), and how does it work?
14. Have you created a Jenkins pipeline for your project?
15. How do you attach policies to IAM users, either individually or by group?
16. What type of deployment strategies are you using in your project?
17. Have you used any tools to create customized Amazon Machine Images (AMIs)?
18. What is connection draining, and how does it work?
19. How does an Elastic Load Balancer (ELB) distribute traffic?
20. What is auto-scaling, and how does it work?
21. Can you describe the different types of Load Balancers and provide examples?
22. What is the maximum runtime for a Lambda function?
23. What is the maximum memory size for a Lambda function?
24. How can you increase the runtime for a Lambda function?
25. What automations have you performed using Lambda in your project?
26. Why did you choose Terraform over Boto3 for infrastructure provisioning?
27. What modules have you used in your Lambda function?
28. Have you created an SNS topic for your project?
29. If you've exhausted IP addresses in your VPC, how would you provision new resources?
30. What is Groovy, and how is it used in Jenkins?
31. Why do you use Groovy in Jenkins, and where do you save Jenkins files?
32. What is Ansible, and what is its purpose?
33. What language do you use in Ansible?
34. Where do you run Terraform code, remotely or locally?
35. What is the purpose of access keys and secret keys in AWS?
36. What are Terraform modules, and have you used any in your project?
37. What environments have you set up for your project?
38. Do you use the same AWS account for all environments?
39. Do you have separate Jenkins servers for each environment?
40. Where do you write and save your Lambda function code? 


```

## set - 22

```

✅ What are the different components of Kubernetes?
✅ What are Persistent Volumes (PV) and Persistent Volume Claims (PVC)?
✅ What is the difference between StatefulSet and Deployment?
✅ Tell me about different services in Kubernetes.
✅ What is the difference between ClusterIP and NodePort?
✅ How can you achieve auto-scaling in Kubernetes?
✅ What is a Namespace in Kubernetes?
✅ What is a DaemonSet?
✅ What is an Ingress in Kubernetes?
✅ What is ConfigMap in Kubernetes?
✅ What is a Secret in Kubernetes?
✅ How do you securely store credentials in Kubernetes?
✅ What is a Horizontal Pod Autoscaler (HPA) and what metrics does it use?
✅ How does Vertical Pod Autoscaler (VPA) work?
✅ What is the difference between HPA and VPA?
✅ What is Role-Based Access Control (RBAC) in Kubernetes?
✅ How do you debug a failing Pod?
✅ What is a Custom Resource Definition (CRD)?
✅ What are Helm charts, and how do they simplify Kubernetes deployments?
✅ What are the main components of Helm?
✅ What is a Helm Chart, and what does it contain?
✅ What is a Chart.yaml file, and what is its purpose?
✅ What is a values.yaml file, and how does it work?


```


## set - 23

```
1. How good are you with the Docker?
2. Do you know what is Docker file and how to write the Docker file?
3. Could you tell me about your project experience? Like, have you have you deployed using Compass format to the existing or clusters or any Virtual machine somewhere?
4. Do you know about multi staging?
5. What is the purpose of using multi stage to go from?
6. Using the docker file, how you break up the image?
7. Do you know about the Docker volume?
8. Let's say you have a container. This is attached with docker volume.If the container goes down. Will the volume get deleted or what?
9. Have you brought out the containers or services with the Docker Swarm?
10. Could you explain about the difference btwn pod and Statefullset
11. How do you control the source usage of a pod?
12. Could you tell me about the services in Kubernetes? What are the registries?
13. your case, as you said, that, you do what it is as a load balancer. Have you used to the AWS? Used AWS?
14. Could you tell me what is Ingress?
15. I'm writing a deployment file. Mhmm. And then, I want the volume for the pod. How do you do it?
16. let's say, without storage class can be able to create a PVC and pv?
17. Let's say you are managing a Kubernetes cluster. Okay. But the number of request to your application is increasing steadily. Mhmm. Okay. So how do you scale the application to handle the group?
18. So how do you ensure that the data persistent? You know, even after pod restarts, right, on deletion?
19. how does web application connect with my secret database, which is running it back end? How can you connect.
20. What command do you use to check? How much does the port has used the CPU usage and the usage? How do you check?
21. If it is multiple How do you check which pod is running in which node?
22. are you aware of, Terraform? Like, have you worked with Terraform before?
23. Can you please, like, describe the work we could do using Terraform?
24. which cloud you work on?
25. Do you configure any agents in the Jenkins master, like, maybe some dynamic, cloud in it, like, so that, like, whenever we build something, it will run on some your Docker container or Kubernetes forward?
26. Are you aware of, Ansible scripts?
27. One question. Have you ever been part of, certificate managements?Like, renewing the certificates?
28. in your organization, how will you guys pick up the UI for the application using AWS?
29. Was those created manually or using CloudFormation out there?
30. let's say you have VPC.Okay? You have pub subnets and private subnets. And in both subnet, you have some machines running. Okay. Private subnet machines does not have a Internet connection.So how do you make sure that, you wanna download something?How does that machine get Internet connection?

```
## set - 24

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
25. What tools have you used to backup?
26. Have you used s3?What was the purpose for? and classes?
27. what other AWS services have you used?
28. Have you used load balancing based on route 53?

```

## set - 25

```

1. what are your roles and responsibilities?
2. How do you integrate ansible to deploy your application.
3. How where do you store statefile and write script for backend dynamodb and S3 ?
4. I have created 5 instance with terraform, manually deleted two resources . How many resources will terraform create once we apply terraform?
5. We have created a terraform resources file to create 50 resources but due to some issues it failed to create all resources. What happens when we reapply ? Will it create additional resources or will it recreate from the start?
6. What is taint in terraform?
7. How can you bring existing resources to manage with terraform?
8. How do you run an application while recreating instance.
9. How can you check the application status creating along with terraform?
8. Write a Jenkins pipeline used in your current project.
9. How do you secure jenkins ?
10. Write a shell script to find an error pattern in a file and send an email?
11. Write a script to delete last 7 days old and more than 100 mb files.
12. Write script to schedule a job to run backup file?
13. Write a script to get back to save with time stamp?
12. Write a script to check if the nginx service is working or not.
13. How do you trouble shoot applications running.
14. What is image pull back error and how do you trouble shoot in k8s
15. How is the application high available in eks ?
16. Where to you deploy the load balancer front end, back end?
17. On which layer SSL/TLS certificates are attached.
18. What is the architecture of the current project in eks ?
19. How do you connect to private subnet instances?
20. How do you configure an EC2 connect S3 bucket?
21. What happens when you don't provide variables in terraform files? How will it take variables?
22. How do you override existing environment variables in terraform?
23. How do you deploy an application in EC2 Instance without jenkins.
24. Explain how you configure ansible to deploy an application with jenkins?

```
## set - 26

```
1.A critical application is running slow, and customers are complaining. How would you troubleshoot the issue?

2.A deployment went wrong and broke production. How would you roll back quickly?

3.Your monitoring tool is not alerting on system failures. How would you debug this?

4.A developer accidentally ran a script that deleted all files in a cloud storage bucket. What steps would you take to recover and prevent this in the future?

5.Your production Kubernetes cluster is running out of resources. How would you identify and resolve the issue?

6.Your CI/CD pipeline takes too long to complete. How would you speed it up?

7.A newly deployed feature is breaking production, but it works in staging. How would you investigate the issue?

8.How would you implement blue-green deployments in a Kubernetes environment?

9.What are the best practices to prevent deployment failures in a CI/CD pipeline?

10.A rollback was triggered due to an issue, but the rollback also failed. What steps would you take?

11.A security scan in your pipeline detected vulnerabilities in dependencies. How would you handle this?

12.How do you implement least privilege access in AWS/Azure for DevOps pipelines?

13.How would you secure a Kubernetes cluster running in the cloud?

14.What are the security risks of using third-party container images, and how do you mitigate them?

15.You suspect a security breach in your cloud infrastructure. How would you investigate and contain the issue?

16.Your cloud costs have increased unexpectedly. How would you identify and optimize the costs?

17.How do you handle secret management in a cloud-native environment?

18.What strategies would you use to migrate on-prem workloads to the cloud with minimal downtime?

19.A specific region of your cloud provider is down. How would you ensure high availability?

20.How would you implement auto-scaling in a cloud environment for a high-traffic application?

21. A new junior engineer accidentally deleted a production database. What immediate actions would you take, and how would you prevent this from happening again? 


```
## Set- 27

```

🔹 Can you explain the different types of 𝗹𝗼𝗮𝗱 𝗯𝗮𝗹𝗮𝗻𝗰𝗲𝗿𝘀?
🔹 What are the various 𝗢𝗦𝗜 𝗹𝗮𝘆𝗲𝗿𝘀, and how do they 𝗳𝘂𝗻𝗰𝘁𝗶𝗼𝗻?
🔹 Between the 𝗢𝗦𝗜 and 𝗧𝗖𝗣/𝗜𝗣 𝗺𝗼𝗱𝗲𝗹𝘀, which one is 𝗯𝗲𝘁𝘁𝗲𝗿 𝘁𝗼 𝗶𝗺𝗽𝗹𝗲𝗺𝗲𝗻𝘁 and why?
🔹 How do you i𝗻𝘀𝘁𝗮𝗹𝗹 𝗚𝗿𝗮𝗳𝗮𝗻𝗮 and 𝗰𝗼𝗻𝗳𝗶𝗴𝘂𝗿𝗲 it to display logs and metrics?
🔹 Given two front-end services and 15 back-end services in a 𝗚𝗶𝘁𝗟𝗮𝗯 𝗿𝗲𝗽𝗼𝘀𝗶𝘁𝗼𝗿𝘆, how would you deploy them in 𝗞𝘂𝗯𝗲𝗿𝗻𝗲𝘁𝗲𝘀?
🔹 What is the key difference between 𝗛𝗼𝗿𝗶𝘇𝗼𝗻𝘁𝗮𝗹 𝗦𝗰𝗮𝗹𝗶𝗻𝗴 𝗮𝗻𝗱 𝗩𝗲𝗿𝘁𝗶𝗰𝗮𝗹 Scaling?
🔹 What exactly is the 𝗧𝗖𝗣/𝗜𝗣 𝗺𝗼𝗱𝗲𝗹?
🔹 What is a 𝗡𝗲𝘁𝘄𝗼𝗿𝗸 𝗘𝗻𝗱𝗽𝗼𝗶𝗻𝘁 𝗚𝗿𝗼𝘂𝗽?
🔹 How would you set a password for a user on a 𝗖𝗼𝗺𝗽𝘂𝘁𝗲 𝗘𝗻𝗴𝗶𝗻𝗲 𝗶𝗻𝘀𝘁𝗮𝗻𝗰𝗲?
🔹 What is the purpose of a 𝘀𝗵𝗲𝗯𝗮𝗻𝗴 𝗶𝗻 𝗮 𝘀𝗰𝗿𝗶𝗽𝘁?
🔹 What are the different types of services in 𝗞𝘂𝗯𝗲𝗿𝗻𝗲𝘁𝗲𝘀?
🔹 Can you define a 𝗡𝗲𝘁𝘄𝗼𝗿𝗸 𝗚𝗮𝘁𝗲𝘄𝗮𝘆?
🔹 What is 𝗖𝗜𝗗𝗥, and why is it used?
🔹 How many bytes are there in 𝗜𝗣𝘃𝟲 𝗮𝗻𝗱 𝗜𝗣𝘃𝟰?
🔹 What differentiates a 𝗹𝗼𝗴𝗶𝗰𝗮𝗹 𝗮𝗱𝗱𝗿𝗲𝘀𝘀 from a physical address?
🔹 How do a 𝗠𝗔𝗖 𝗮𝗱𝗱𝗿𝗲𝘀𝘀 and an IP address differ in function?
🔹 What is the use of the 𝘁𝗲𝗿𝗿𝗮𝗳𝗼𝗿𝗺 𝗴𝗿𝗮𝗽𝗵 command?
🔹 What is a null resource in 𝗧𝗲𝗿𝗿𝗮𝗳𝗼𝗿𝗺?
🔹 How does a 𝗧𝗲𝗿𝗿𝗮𝗳𝗼𝗿𝗺 module differ from a template?
🔹 How can a 𝗽𝗶𝗽𝗲𝗹𝗶𝗻𝗲 be configured to run manually?
🔹 How would you write a 𝗗𝗼𝗰𝗸𝗲𝗿𝗳𝗶𝗹𝗲 to build a 𝗡𝗼𝗱𝗲.𝗷𝘀 project?
🔹 Why is it beneficial to copy 𝗽𝗮𝗰𝗸𝗮𝗴𝗲.𝗷𝘀𝗼𝗻 before other files in a Dockerfile?
🔹 What is the difference between package.json and 𝗽𝗮𝗰𝗸𝗮𝗴𝗲-𝗹𝗼𝗰𝗸.𝗷𝘀𝗼𝗻 in 𝗡𝗼𝗱𝗲.𝗷𝘀?


```

## Set - 28
```
1.) How many NAT Gateways are needed for two public & two private subnets in a single VPC? Min & max?

2.) Explain TTL in DNS—how does it work, and when do we use it? Explain the Flow.

3.) How does weighted routing work in LB?

4.) How Docker is operable on a Linux machine? Explain the docker architecture components.

5.) There are 1 Master & 3 Worker nodes—if the master fails, what 
happens? Will pods keep running or they will crash?

6.) In K8s, as etcd is a key-value store db, can write something manually on it?

7.) How to roll back a failed deployment in Docker & K8s?

8.) How does SSL work (Certbot, Let's Encrypt, AWS)? Explain the Flow.

9.) What are the top 5 infra attacks, and how do you mitigate them?

10.) If the tfstate file is lost, what do you do? With & without backup?

11.) In Linux systems there is the term Load Average? what does that mean? how it is being calculated? and in what format the load average output is?

12.) One of your worker nodes is not joining the cluster. How would you debug the issue?

```
## Set - 29
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

## Day - 30

```
1. Two employees work in different shifts (10 AM–5 PM and 6 PM–2 AM). How do you provide AWS access based on timing?
2. What is the default port number for DynamoDB?
3. What is Ingress in Kubernetes, and how can we access applications deployed on-premises?
4. What is the port range for NodePort mode?
5. Do LoadBalancers work in on-premises setups?
6. What’s the difference between ECS and EKS?
7. How do you store secrets in Jenkins and use them in pipelines?
8. Write a shell script to find prime numbers.
9. Terraform code to launch an EC2 instance.
10. Are you familiar with custom IAM policies? Can you write one?
11. What is PV and PVC in Kubernetes? Which one comes first, and why?
12. Explain RBAC – what is it, its uses, and how is it configured?
13. How can we expose on-premise applications?
14. What is the purpose of Jenkins shared libraries? Explain with steps.
15. What is VPC peering and how does it work?
16. Can we add storage to an existing EC2 instance and how, steps to add?
17. What are the core components of Kubernetes, and which are the most important?
18. Two users access the same application – one has low latency, the other high. How would you troubleshoot?
19. How do we connect services deployed on the cloud with those on-premises?
20. How do we know the entire process executed that we have mentioned in Jenkins? What are the possible ways to know this?
21. How can we configure GitHub in Jenkins using both Freestyle and Pipeline jobs?

```

## DAY - 31
```
🔹Explain state file in Terraform, where do you store it in your environment
🔹What are best practices of storing state files
🔹What are modules in Terraform, write down all the files which exist in your terraform folder when you build .tf files.
🔹What is difference between variables.tf and .tfvars file
🔹 How do you manage different environments in terraform configuration like Dev, Staging and Prod
🔹Difference in Merge and Rebase in Git
🔹What is the use of git stash command
🔹Have you worked on DR, what is the difference in RTO and RPO
🔹What is the use of Hub and Spoke model
🔹What AWS services have you used.
If I do not want to use Autoscaling policies to Autoscale EC2, is there any other way like using Cloudwatch etc?
🔹I have written a TF configuration for an EKS Cluster with a service account resource also created, I know that the EKS resource should be created after the IAM role so that the role can access the cluster, what is the solution to this problem
🔹Have you encountered a scenario where the IAM role has not propogated completely even though the trust policy and all permissions were properly created?
🔹When an EKS Cluster is deployed, what files are created and what is the significance of Karpenter in it.
🔹How do you control specifically which resources are to be destroyed and which ones are to be kept.
🔹write Terraform code to Deploy an EKS cluster, Helm chart and Datadog agent. Use the agent to setup monitoring.
🔹How do i control the deployment of a second terraform resource apart from the depends_on feature, and can I time delay its deployment?


```
## Day - 32

```
1. Two employees work in different shifts (10 AM–5 PM and 6 PM–2 AM). How do you provide AWS access based on timing?
2. What is the default port number for DynamoDB?
3. What is Ingress in Kubernetes, and how can we access applications deployed on-premises?
4. What is the port range for NodePort mode?
5. Do LoadBalancers work in on-premises setups?
6. What’s the difference between ECS and EKS?
7. How do you store secrets in Jenkins and use them in pipelines?
8. Write a shell script to find prime numbers.
9. Terraform code to launch an EC2 instance.
10. Are you familiar with custom IAM policies? Can you write one?
11. What is PV and PVC in Kubernetes? Which one comes first, and why?
12. Explain RBAC – what is it, its uses, and how is it configured?
13. How can we expose on-premise applications?
14. What is the purpose of Jenkins shared libraries? Explain with steps.
15. What is VPC peering and how does it work?
16. Can we add storage to an existing EC2 instance and how, steps to add?
17. What are the core components of Kubernetes, and which are the most important?
18. Two users access the same application – one has low latency, the other high. How would you troubleshoot?
19. How do we connect services deployed on the cloud with those on-premises?
20. How do we know the entire process executed that we have mentioned in Jenkins? What are the possible ways to know this?
21. How can we configure GitHub in Jenkins using both Freestyle and Pipeline jobs?
```
## Kube

```
When I started learning Kubernetes, I was overwhelmed by the vast ecosystem. After helping several teams adopt Kubernetes, I've created this 2-month learning path 

𝗜𝗻𝘁𝗿𝗼𝗱𝘂𝗰𝘁𝗶𝗼𝗻 (𝗪𝗲𝗲𝗸 𝟭)
- Overview of Kubernetes architecture
- Why choose Kubernetes?
- Key concepts and terminologies
- Container fundamentals
- Understanding Kubernetes alternatives

𝗦𝗲𝘁𝘁𝗶𝗻𝗴 𝘂𝗽 𝗞𝘂𝗯𝗲𝗿𝗻𝗲𝘁𝗲𝘀 (𝗪𝗲𝗲𝗸 𝟮)
- Deploying your first application
- Choosing between managed providers (EKS, GKE, AKS)
- Installing a local cluster (Minikube/Kind)
- Basic cluster operations

𝗥𝘂𝗻𝗻𝗶𝗻𝗴 𝗔𝗽𝗽𝗹𝗶𝗰𝗮𝘁𝗶𝗼𝗻𝘀 (𝗪𝗲𝗲𝗸 𝟯-𝟰)
- Working with Pods
- Understanding ReplicaSets
- Managing Deployments
- Implementing StatefulSets
- Creating Jobs and CronJobs

𝗦𝗲𝗿𝘃𝗶𝗰𝗲𝘀 𝗮𝗻𝗱 𝗡𝗲𝘁𝘄𝗼𝗿𝗸𝗶𝗻𝗴 (𝗪𝗲𝗲𝗸 𝟱)
- External access to services
- Load balancing fundamentals
- Pod-to-Pod communication
- Network policies and security

𝗖𝗼𝗻𝗳𝗶𝗴𝘂𝗿𝗮𝘁𝗶𝗼𝗻 𝗮𝗻𝗱 𝗥𝗲𝘀𝗼𝘂𝗿𝗰𝗲 𝗠𝗮𝗻𝗮𝗴𝗲𝗺𝗲𝗻𝘁 (𝗪𝗲𝗲𝗸 𝟲)
- Injecting Pod configurations with ConfigMaps
- Managing secrets for sensitive data
- Setting resource requests and limits
- Assigning quotas to namespaces
- Monitoring resource usage

𝗦𝗲𝗰𝘂𝗿𝗶𝘁𝘆 𝗮𝗻𝗱 𝗠𝗼𝗻𝗶𝘁𝗼𝗿𝗶𝗻𝗴 (𝗪𝗲𝗲𝗸 𝟳)
- Role-based access control (RBAC)
- Network security implementation
- Container and Pod security
- Security scanners and best practices
- Setting up monitoring and logging
- Implementing observability
- Resource health tracking

𝗔𝗱𝘃𝗮𝗻𝗰𝗲𝗱 𝗢𝗽𝗲𝗿𝗮𝘁𝗶𝗼𝗻𝘀 (𝗪𝗲𝗲𝗸 𝟴)
- Implementing autoscaling
 - Horizontal Pod Autoscaler (HPA)
 - Vertical Pod Autoscaler (VPA)
 - Cluster Autoscaling
- Storage and Volumes
 - CSI Drivers
 - Stateful Applications
- Deployment Patterns
 - CI/CD Integration
 - GitOps practices
 - Working with Helm Charts
 - Implementing Canary Deployments
 - Blue-Green Deployment strategies
 - Managing Rolling Updates/Rollbacks

𝗪𝗲𝗲𝗸𝗲𝗻𝗱 𝗣𝗿𝗮𝗰𝘁𝗶𝗰𝗲 𝗣𝗿𝗼𝗷𝗲𝗰𝘁𝘀:
1. Week 2: Deploy a multi-container web application
2. Week 4: Implement service mesh and monitoring
3. Week 6: Set up automated CI/CD pipeline
4. Week 8: Deploy a production-ready microservices application


```
