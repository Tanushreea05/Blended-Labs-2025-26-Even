# Lab 3 – Introduction to Amazon Elastic Compute Cloud (EC2)

## Author

* **Name**: Tanushree A
* **Register Number**: 212223100057
* **Date of Submission**: 27.02.2026

---

## Objective

The objective of this experiment is to understand the fundamentals of Amazon Elastic Compute Cloud (EC2). This lab focuses on launching and managing a virtual server, understanding instance types and AMIs, connecting to an EC2 instance, monitoring its status, and performing basic instance operations such as start, stop, and terminate.

---

## Prerequisites

* Basic understanding of cloud computing concepts
* AWS account or AWS Academy Lab access
* Web browser with internet connectivity
* Basic knowledge of Linux commands (optional)

---

## Tools Used

* AWS Management Console
* Amazon EC2
* Key Pair
* Security Group
* SSH Client (PuTTY / Terminal)

---

## Tasks Performed

### Task 1: Explore Amazon EC2 Dashboard

Explore the EC2 service dashboard in the AWS Management Console. Observe the different sections such as Instances, AMIs, Instance Types, Key Pairs, Security Groups, and Elastic IPs.

---

### Task 2: Launch an EC2 Instance

Launch a new EC2 instance using Amazon Linux 2 AMI. Select an appropriate instance type (t2.micro) under the free tier. Configure basic settings such as instance name, key pair, and security group.

---

### Task 3: Configure Security Group

Configure a security group to allow inbound access:

* SSH (Port 22) from your IP address
* HTTP (Port 80) from anywhere (0.0.0.0/0)

This security group acts as a firewall for the instance.

---

### Task 4: Connect to EC2 Instance

Connect to the running EC2 instance using SSH. Use the downloaded key pair and connect via terminal or PuTTY.

For Amazon Linux:

```
ssh -i "keyname.pem" ec2-user@<Public-IP>
```

---

### Task 5: Perform Basic Instance Operations

Perform the following operations from the EC2 console:

* Stop the instance
* Start the instance
* Reboot the instance

Observe the state changes of the instance.

---

### Task 6: Monitor EC2 Instance

Monitor the EC2 instance using the Monitoring tab. Observe metrics such as CPU utilization, network in/out, and instance status checks.

---

### Task 7: Terminate EC2 Instance

Terminate the EC2 instance after completing the experiment to avoid unnecessary AWS charges.

---

## Workflow (Student Explanation)


1. Create an account on Amazon Web Services and log in to the AWS Management Console.

2. Open the Amazon EC2 dashboard from the Services menu.

3. Click Launch Instance and choose an Amazon Machine Image (AMI).

4. Select an instance type (e.g., t2.micro), configure a key pair, and set up security group rules.

5. Launch the instance and connect to it using SSH (Linux) or RDP (Windows).

---

## Output Screenshots (Attach 3)

### Screenshot 1: EC2 Dashboard / Instance List


<img width="1920" height="1200" alt="image" src="https://github.com/user-attachments/assets/69642af0-bf23-48e7-b683-6adca25007cd" />




<img width="1920" height="1200" alt="image" src="https://github.com/user-attachments/assets/e75fa987-c5e3-4ecc-9642-f0a67fe1e3fd" />




---

### Screenshot 2: SSH Connection to Instance


<img width="1920" height="1200" alt="image" src="https://github.com/user-attachments/assets/e318ffc2-43ba-4084-846f-d9ad2cfb48e7" />


<img width="1920" height="1200" alt="image" src="https://github.com/user-attachments/assets/0412ea31-c076-4f49-9b23-4b7a242cfe4c" />


---

### Screenshot 3: Instance Monitoring / Status

<img width="1920" height="1200" alt="image" src="https://github.com/user-attachments/assets/c4a96c65-77e2-440b-a051-39aeec93cee8" />


<img width="1920" height="1200" alt="image" src="https://github.com/user-attachments/assets/f09a7281-9095-41d4-9b03-b3b6ec63faf8" />


---

## Result 

This experiment provided hands-on experience with Amazon EC2 by demonstrating how to launch, connect, manage, and monitor a virtual server in AWS. It helped in understanding the concept of Infrastructure as a Service (IaaS) and how compute resources can be provisioned and controlled on demand in the cloud.
