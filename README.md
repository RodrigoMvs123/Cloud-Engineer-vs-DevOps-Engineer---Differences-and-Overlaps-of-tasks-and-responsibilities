# Cloud-Engineer-vs-DevOps-Engineer---Differences-and-Overlaps-of-tasks-and-responsibilities

https://www.youtube.com/watch?v=N1-mhvUghb0&t=1s

https://raw.githubusercontent.com/RodrigoMvs123/Cloud-Engineer-vs-DevOps-Engineer---Differences-and-Overlaps-of-tasks-and-responsibilities/main/README.md



DEVOPS Engineer            CLOUD Engineer

Tasks and responsibilities ? 
Same role ? 
2 names for the same role ?


Two different roles 

DEVOPS Engineer             CLOUD Engineer

Overlapping responsibilities and skills 
Defining boundaries between IT roles

Full stack development 
Operations 
Networking 
CI/CD
Monitoring 

Define boundaries between DevOps and Cloud job role
What does a Cloud Engineer ?
What does a DevOps Engineer ?
Overlap tasks ?
Differences ?

Originally, DevOps Engineer was not meant as a separate role

Concept and Set of Principles 

We should implement those DevOps practices  
Software Developer
IT Operation 
Server Administrator 

Different Objectives 

DevOps Engineer 
Make process of releasing software fast, efficient, without bugs

Implement
Test
Build and Package
Deploy to the Developer
Deploy to Test
Release to PROD

X - Manual Approvals 
X - Manual Testing 
X - Manual Security Checks
X- Manual Deployments 

Automate and streamline whole process 

Cloud Engineer 
Create and manage infrastructure on cloud 
App run on this cloud infrastructure ( Data Warehouse )

The need for Cloud Engineers
Cloud Platforms 
Data centers with hundreds of server machines 

Rent Server ( No need to set up infrastructure yourself )
On-demand infrastructure 
DB services 
Storage backup
Cache services 
Managed kubernetes cluster
Docker registries 
CI/CD on cloud 
Geographical regions 
Access management 

Small local cloud platforms 
Larger cloud platforms ( AWS, Google Cloud, Microsoft Azure )   

Create entire setup using cloud platform services
Not need to install and configure things from scratch ( Ex: Setup a docker image registry or installing kubernetes cluster on servers ) 

AWS
Security 
Servers
Storage 
Developer Tools
Containers 
Big Data
IoT
Databases
Machine learning 
You get tons of services that are already configured on top of the actual underline physical infrastructure 

Create and manage own virtual servers
Use managed services
Combine self-managed versus managed

You do not have to set up infrastructure from scratch ( You can use the cloud services for all those things ) 

Learn how to use cloud services 
How to integrate them 
Plug them in into your applications 

AWS
EKS ( Kubernetes Cluster ) 
ECR ( Image Registry )
RDS
CodePipeline 

Microsoft Azure 
AKS
Azure SQL
Azure Pipelines
Azure Artifacts 

Google Cloud

Same services but they work differently and different configuration options 

AWS ( Underline Infrastructure ) 
Servers 
Firewall configuration 
Proxy
Security within your network 

Learn cloud platform services that allow configuration of underline infrastructure 

Configure with Best Practices 
AWS

Reliable and Secured 
EC2
ECR
RDS
EKS

Application setup was not design for such high load
Someone hacks into your set up and delete your data or your configuration 
Or a new developer accidentally mis configure something ruin your aws infrastructure set up

Cloud Engineer Tasks 
Developing and maintaining cloud infrastructure and services 
That is reliable, secure with best practices 

Specialized on a specific cloud 
Cloud Platform specific knowledge needed 
( Cloud Platform are different and their services need to be configured differently )
Specific Knowledge ( To properly configure your infrastructure set up )

AWS Cloud Engineer ( Create and manage infrastructure on cloud )
“Our app should run on AWS cloud”
How to create and set up AWS infrastructure to run the apps ?
Which AWS services ?
Rent services and configure from scratch or use managed services ?

configure a clustered database on servers ?
Use a RDS service ?
Which storage ?
How to map to AWS storage types ? 
How does backup and restore work on AWS ? 
How to secure AWS infrastructure ?

Map company needs and requirements into AWS cloud set up 
“Our app need to be available in al geographic locations”
“Deploy our microservices app on cloud”

Cloud Migrations 
Many companies have an existing on-premise infrastructure, which they want to migrate to cloud 

Building from scratch is often easier than migrating 

Hybrid Cloud 
on-premise 
cloud

Multi Cloud 
AWS
Azure
Using cloud services from different vendors

Redundancy 
If something happens to one AWS Center, you have full backup from Azure

Use strength of each cloud provider 
They want to to use AWS computer resources but the company have lots of internal microsoft applications so they will gonna use Azure

Services need to be connected across cloud platforms 

Cloud Engineer Tasks 
Develop migration strategy 
Create integrations in hybrid or multi cloud environments 
Monitor infrastructure 
Identify, analyze and resolve infrastructure vulnerabilities  

AWS Cost Tracking
Predict and monitor costs  

Infrastructure as Code

X - Manual configuration 
X - No transparency and difficult collaboration 
X - Manually re-create the setup or fix things is tedious, time consuming and error prone

Automate provisioning of infrastructure with code 
Write configuration files that contain infrastructure specifications 
IaC gives you benefits like transparency, consistency, scalability etc

Differences of DevOps and Cloud Engineer 

DevOps Engineers 
Automate software release process 
implement 
test
Build and Package 
Deploy to Developer 
Deploy to Test 
Release to PROD 

Claud Engineers
Automate cloud infrastructure management that is secure, reliable and scalable 

Overlap of DevOps and Cloud Engineers 
Deployment to cloud is part of software release life cycle 
( Part of software release is deployed into to servers on infrastructures )

Deployment of applications into to Cloud 
Make sure cloud infrastructure is configured and managed properly 
To allow for fast deployment 
Automation Testing 
Validating whether deployment works

DevOps Engineers job extends to Cloud Engineer tasks and responsibilities 
To manage the underlying infrastructure 
Monitor ( So the application can be deployed ) 
Secure ( Not running out of resources ) 
Geographically distributed 
Scalable 

If the application is running on kubernetes cluster managed by AWS DevOps engineers would make sure if the cluster if running fine 
Correctly configured 
Security in place 

DevOps Engineers 
Uses also IaC tools ( To automate infrastructure management, monitoring etc ) 

Only the parts that affect the release process of the application 
Cloud infrastructure management that directly affect how fast the application can be released, deployed, recovered etc
It is part of DevOps Engineers Tasks 

Release management 
Infrastructure management 
Backup and restore management 
Cost over side 

DevOps Engineer ( Releasing applications fast ) 
“Devops Engineer - DEV TEST PROD” - Focus on building automated process on top
Release Management
Monitoring and Logging 
CI/CD Pipeline 
Infrastructure as a Code 
Cloud Engineer ( Reliable secured infrastructure )
Manage 
Secure
Monitor
Infrastructure 
Scalable 
Cloud Migrations 
Cost Monitoring 
Backup and restore 



