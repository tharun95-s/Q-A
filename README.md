# Q-A
Interview Questions Devops


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

From <https://www.linkedin.com/posts/yogeshk5_devopsengineer-cloudengineer-devopshiring-activity-7302893132726067201-r0Ce/?utm_source=social_share_send&utm_medium=android_app&rcm=ACoAADdktgEBabDiZokT62WNaj_Rx2idJEMepv4&utm_campaign=whatsapp> 

L1 Questions:

1, What is the purpose of creating S3 bucket policies?
2, How do you maintain the lifecycle of an S3 bucket?
3, In CloudWatch, what is the use of log groups and log trails?
4, In Terraform, what is the purpose of init, plan, and apply commands?
5, If the Terraform state file is accidentally deleted, what happens?
6, In Airflow, if a job fails, how do you debug it?
7, If you're facing performance issues on a server, how do you troubleshoot them?
8, In Python, what are lists and tuples?
9, In Git, explain the push and pull commands.
10, What is the use of Git tags?
11, What are the different types of branches in Git?
12, How do you write an Ansible playboo k, and what kind of requirements do you get from clients?


L2 Questions:

1, Explain EC2 instances and handling multiple VPCs.
2, What are Network ACLs and Security Groups, and how do they differ?
3, In Kubernetes, if a pod is in a pending state, how do you troubleshoot?
4, If Docker containers are consuming too much disk space, how do you fix it?
5, In Linux, how do you attach and detach a filesystem?
6, How do you print the last 15 lines of a file in Linux?
7, How do you enable passwordless authentication between two servers?
8, How do you configure AWS RDS, and what factors do you consider (size, requirements, etc.)?
9, How much data is stored in your RDS MySQL?
10, How many masters and slaves are in RDS?
11, How do you configure a Grafana dashboard?
12, What kind of CI/CD pipelines are you familiar with?
13, Explain Declarative vs. scripting pipelines.

From <https://www.linkedin.com/posts/manoj-k-415848a9_interview-cloud-devops-activity-7307574739013709825-MuzX/?utm_source=social_share_send&utm_medium=android_app&rcm=ACoAADdktgEBabDiZokT62WNaj_Rx2idJEMepv4&utm_campaign=whatsapp> 

1, cicd workflow, what kind of pipeline.
2, use of webhook
3, purpose of webhook
4, stages of pipeline...
5, shared libraries in jenkins?
6, how do we define shared libraries?
7, how are shared libraries written?
8, how do you define a pipeline and call it?
9, what kind of app you deploy on the pipeline?
10, basic structure, folder structure of helm?
11, what command are you using deployment in helm
12, in the Jenkins pipeline, the pipeline is running successfully but the build is not happening, what are the issues?
13, in kubernetes, what are the errors you are getting, why they come and how you resolve?
14, explain the crash loop back off,
15, image pull error?
16, command to go inside a pod?
17, how can you create the kubernetes class?
18, what are the steps to create the cluster?
19, what is the master node and other node?
20, code to create a cluster using terraform?
21, stages in docker images?
22, DB entry point, CMD 
23, why do we use entrypoint, CMD
24, DB ec2, eks, ecs
25, command to connect ecs
26, which tool are you using for deployment?
27, which registry for storing the docker images?

Level 2 -

1, Branching strategy?
2, your release branch will break, then how u will avoid this kind of issues, then how do you merge?
3, in production having some bugs, how will you resolve?
4, typical deployment flow?
5, cicd workflow?
6, how do we do a full quality check?
7, jenkins file, different stages...
8, shared libraries in jenkins file?
9, typical structure of shared libraries...
10, are you aware of security scanning tools?
11, how do you pass the environment variables on docker build command.
12, what services do you use for storing the images?
13, DB, how do you establish the connection?
14, how do you scan the images at the registry level?
15, any extension you are using for image scanning?
16, authentication of eks cluster?
17, storing the secrets?
18, how to create lambda function, how it's taking the artifacts.
19, options on lambda to push the artifacts?
20, what is email signing and helm chart signing?
21, which tool for signing the helm chart?

From <https://www.linkedin.com/feed/update/urn:li:activity:7340328720248774656/> 


𝗥𝗼𝘂𝗻𝗱 𝟭: 𝗧𝗲𝗰𝗵𝗻𝗶𝗰𝗮𝗹 𝗦𝗰𝗿𝗲𝗲𝗻𝗶𝗻𝗴
1. Explain the CI/CD workflow you follow and the kind of pipeline you use. How do you define and invoke pipelines in Jenkins?
2. What are shared libraries in Jenkins, and how are they written and defined?
3. What kind of applications do you deploy using Jenkins pipelines, and what deployment tools do you use?
4. If the Jenkins pipeline runs but the build doesn’t happen, what possible issues could be causing it?
5. What is the purpose of a webhook, and how is it used in a CI/CD pipeline?
6. How do you create and manage Kubernetes clusters (using tools like Terraform), and what are the master and worker nodes?
7. What are common Kubernetes errors you’ve faced (like CrashLoopBackOff, ImagePullError), and how did you resolve them?
8. What is the command to access a pod and how can you define or create a Kubernetes class or object?
9. Explain the folder structure of a basic Helm chart. What commands do you use to deploy with Helm?
10. What are the stages in a Docker image build? Why do we use ENTRYPOINT and CMD instructions?
11. How do you manage and connect services like DBs, EC2, EKS, or ECS? Include the command to connect to ECS.
12. Which container registry do you use for storing Docker images?

𝗥𝗼𝘂𝗻𝗱 𝟮: 𝗜𝗻-𝗱𝗲𝗽𝘁𝗵 𝗧𝗲𝗰𝗵𝗻𝗶𝗰𝗮𝗹 𝗦𝗰𝗿𝗲𝗲𝗻𝗶𝗻𝗴
1. What branching strategy do you follow, and how do you handle merges to avoid breaking the release branch? If a bug appears in production, what’s your approach to resolving it?
2. Describe your typical deployment flow and CI/CD workflow. What stages do you define in your Jenkins pipeline, and how do you ensure full quality checks during deployment?
3. How do you use Jenkins shared libraries? Explain their typical structure and how they are integrated into your Jenkinsfiles.
4. Are you aware of security scanning tools? How do you scan Docker images—both during build and at the registry level? Are you using any extensions or tools for image scanning?
5. How do you pass environment variables during Docker build commands? What services do you use for storing Docker images?
6. How do you establish a connection with databases in your deployments or infrastructure setup?
7. How do you handle authentication for EKS clusters and store secrets securely in your environment?
8. How do you create AWS Lambda functions and manage the artifacts for deployment? What options do you use to push artifacts to Lambda?
9. What is email signing and Helm chart signing? Which tools do you use to sign Helm charts?

From <https://www.linkedin.com/in/dipakshekokar/recent-activity/all/> 

1. What is DevOps Lifecycle?
2. Have you used any Linux Flavors, if yes, which one?
3. What is the command to change the ownership and permission of a file or directory in Linux?
4. How do you manage and view running processes in Linux?
5. What is SSH?
6. What is DNS (Domain Name System), and how does it work?
7. What is NAT(Network Address Translatioj), and why is it used?
8. Explain the difference between TCP and UDP Protocols?
9. What os Git and how do we use it in DevOps?
10. Explain the workflow of how to push the code from a local machine?
11. How do you revert a commit that you made in your repository?
12. What is a Branch in a Repository?
13. What cloud you are familiar with?
14. What is VPC in cloud?
15. What is the difference between a Private and Public Subnet and what differentiates it?
16. What is the Deifference between reserved instance and spot instances?
17. What is CloudFormation (AWS) ?
18. What are the popular IaC tools have you used?
19. What is the difference between Terraform & Ansible?
20. What is a playbook in Ansible?
21. What is a state file in terraform?
22. What is Terraform Remote state backend?
23. What is the Difference between Virtualization and containerization?
24. What problem does Docker Solves?
25. What is Dockerfile and why do we use it?
26. Explain the workflow of how a Docker Container is created?
27. How do you manage multiple Containers?
28. What is Ci and CD in CICD?
29. What CICD tools have you used in the past?
30. How will you create a CICD pipeline to update the website or app on every commit to a particular branch? (mostly asked in the coding test)?
31. Explain staging, production and testing environment.?
32. What is a Blue Green Deployment?
33. Explain Canary Deployment?
34. What is the biggest issue you faced, how did you resolve it.?
35. How do you scale your application?
36. How do you rollback if something fails?
37. How do you automate Deployments?
38. Which tools have you used for automating deployments?
39. Have you written any Jenkins Pipeline from scratch?
40. Mention some plugins you have used in Jenkins?
41. What is CI/CD?
42. How can you create backup and copy files in Jenkins?
43. Assume you have 2 Jenkins jobs. So, the first job completed successfully but the 2nd job failed. What will you do?
44. Can you tell me the process to integrate git with Jenkins?
45. Can you tell me what is DSL in Jenkins?
46. Why we use Jenkins instead of Bamboo? Difference between them?
47. How to deploy a custom build of a code plugin to Jenkins?
48. What is the use of Jenkins home directory?
49. How do take backup of Jenkins Jobs?
50. What is the way to configure Jenkins nodes agent with Jenkins master?

From <https://www.linkedin.com/posts/activity-7303764432113803264-PAyv/?utm_source=social_share_send&utm_medium=android_app&rcm=ACoAAFeDmFABD6yjmDptCN8Z7jJyr2Zxyf-aB6k&utm_campaign=whatsapp> 
![image](https://github.com/user-attachments/assets/c1626875-686e-4141-b554-33f05b19b716)

