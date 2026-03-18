# Lab 6 – Scale and Load Balance Your Architecture

## Title

Scale and Load Balance Your Architecture


Author : Tanushree A

Reg no : 212223100057 

Date : 17.03.2026

---

## Objective

The objective of this lab is to understand how to design a scalable and highly available architecture on AWS using Auto Scaling and Elastic Load Balancing. This experiment focuses on distributing incoming traffic across multiple EC2 instances, automatically scaling resources based on demand, and validating fault tolerance.

---

## Prerequisites

* Basic knowledge of Amazon EC2 and VPC
* Completion of previous labs (IAM, EC2, EBS, Database Server)
* AWS Academy Lab access
* Stable internet connection

---

## Tools Used

* AWS Management Console
* Amazon EC2
* Elastic Load Balancer (ELB / ALB)
* Auto Scaling Groups (ASG)
* Amazon CloudWatch

---

## Tasks Performed

### Task 1: Review Existing Architecture

Students review the existing EC2-based application architecture created in previous experiments.

### Task 2: Create a Launch Template

Students create a launch template that defines the EC2 instance configuration including AMI, instance type, security group, and user data.

### Task 3: Create an Auto Scaling Group

Students create an Auto Scaling Group using the launch template and configure minimum, maximum, and desired instance capacity.

### Task 4: Configure an Application Load Balancer

Students create an Application Load Balancer and configure target groups for routing traffic to EC2 instances.

### Task 5: Register Auto Scaling Group with Load Balancer

Students attach the Auto Scaling Group to the target group of the load balancer.

### Task 6: Configure Scaling Policies

Students configure scaling policies based on CPU utilization using Amazon CloudWatch alarms.

### Task 7: Test Load Balancing and Scaling

Students test the setup by generating traffic and observing automatic scaling and load distribution.

---

## Workflow (To be filled by Student)

1.Create Launch Template

2.Create Application Load Balancer

3.Create Auto Scaling Group

4.Configure Scaling Policy

5.Test Load Balancing and Scaling

---

## Output Screenshots 

<img width="1920" height="1200" alt="image" src="https://github.com/user-attachments/assets/96257ca1-5b12-4ed0-a865-8d7996ab4baf" />


<img width="1920" height="1200" alt="image" src="https://github.com/user-attachments/assets/874bca70-fe0a-4cd9-8bec-8de2816eb295" />


<img width="1920" height="1200" alt="image" src="https://github.com/user-attachments/assets/a8c5899c-43a9-46ae-9373-1fdeef44258f" />


<img width="1920" height="1200" alt="image" src="https://github.com/user-attachments/assets/c9859fb1-c4e0-4353-83ad-72ed3c1a9db3" />


<img width="1920" height="1200" alt="image" src="https://github.com/user-attachments/assets/fbdfe506-5085-4195-9c35-c4f79f50755e" />


<img width="1920" height="1200" alt="image" src="https://github.com/user-attachments/assets/3daacbe7-1491-4c88-bc90-dd63f500008a" />


<img width="1920" height="1200" alt="image" src="https://github.com/user-attachments/assets/871996cc-0422-4a51-ad8e-91eef568194d" />


<img width="1920" height="1200" alt="image" src="https://github.com/user-attachments/assets/778ae5dd-bb4a-4a9a-a14b-e295836747f1" />


<img width="1920" height="1200" alt="image" src="https://github.com/user-attachments/assets/91f55ad2-f753-41fb-9d70-bae169f315af" />


<img width="1920" height="1200" alt="image" src="https://github.com/user-attachments/assets/7f315d5a-808a-4630-bcc0-17c88ac131ae" />


---


## Result

This experiment demonstrated how to build a scalable and fault-tolerant cloud architecture using Auto Scaling Groups and Elastic Load Balancing. The system automatically adjusted resources based on workload and ensured continuous service availability by distributing traffic across multiple instances.
