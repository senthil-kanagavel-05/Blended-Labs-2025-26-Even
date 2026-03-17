# Lab 3 – Introduction to Amazon Elastic Compute Cloud (EC2)

## Author

* **Name**: SENTHIL KANAGAVEL BALASUNDARAM
* **Register Number**: 212223060254
* **Date of Submission**: 17/03/2026

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

## Output Screenshots (Attach 3)

### Screenshot 1: EC2 Dashboard / Instance List

<img width="1643" height="845" alt="Screenshot 2026-02-27 223639" src="https://github.com/user-attachments/assets/f8311234-c712-45ca-a78d-f6bb3b95e8c5" />

<img width="1630" height="811" alt="Screenshot 2026-02-27 223731" src="https://github.com/user-attachments/assets/7fe87298-c97d-4a17-9fcf-ec30a2e959c2" />

### Screenshot 2: SSH Connection to Instance

<img width="1638" height="831" alt="Screenshot 2026-02-27 223806" src="https://github.com/user-attachments/assets/e3bb52b2-d70e-4421-a179-3823546a6619" />

### Screenshot 3: Instance Monitoring / Status

<img width="1325" height="651" alt="Screenshot 2026-02-27 224110" src="https://github.com/user-attachments/assets/ee22e6e9-2458-4b29-b75f-fa6918f452dc" />

<img width="1250" height="642" alt="Screenshot 2026-02-27 223954" src="https://github.com/user-attachments/assets/c88b80c8-873f-490f-baee-c5f27b79fc05" />


## Result 

This experiment provided hands-on experience with Amazon EC2 by demonstrating how to launch, connect, manage, and monitor a virtual server in AWS. It helped in understanding the concept of Infrastructure as a Service (IaaS) and how compute resources can be provisioned and controlled on demand in the cloud.
