# Highly Available Architecture

## 🌟 Overview
**Scenario**<br/>
MediCare Hub is a lightweight medical application used by clinics to manage patient records and appointment tracking. Originally hosted using traditional infrastructure, it lacked fault tolerance and high availability. Any single EC2 or database failure could lead to downtime and loss of access to critical medical data.

To ensure reliability and resilience, the application is now being **lifted and shifted to AWS**, using best practices from the **Reliability Pillar of the AWS Well-Architected Framework**. The goal is to build an infrastructure that auto-recovers from failures and continues to serve users even during disruptions like instance crashes or Availability Zone (AZ) outages.

**Your Role**<br/>
In this project, you’ll take on the role of a **Solutions Architect focused on reliability engineering**. Your mission is to rearchitect the app’s infrastructure to ensure it remains available and self-healing, even in the event of failures while still being cost-efficient and scalable.

You’ll deploy a highly available web application stack across multiple AZs, with intelligent DNS routing and health checks, all monitored via CloudWatch.

## 🛠️ Services used
* **Amazon EC2**: Auto Scaling app instances across multiple AZs
* **Application Load Balancer (ALB): Distribute traffic and monitor instance health
* **Amazon RDS (Multi-AZ)**: Highly available relational database
* **Amazon Route 53**: DNS routing with health checks and failover
* **Amazon S3**: Backup for DNS Failover
* **Amazon EFS**: Shared storage across EC2 instances

## ☁️ AWS Architecture

## &rarr; Final Result

<!-- ![alt text](design/igw.png) -->
