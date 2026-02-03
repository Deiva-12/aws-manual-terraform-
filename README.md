# AWS-EC2-Terraform

AWS EC2 Manual vs Terraform – Hands-on Guide

## Objective

The goal of this task is to:

Learn AWS core concepts

Launch an EC2 instance manually using AWS Console

Provision an EC2 instance using Terraform

Understand the difference between manual AWS setup and Infrastructure as Code (IaC)

---

## AWS Overview

**AWS (Amazon Web Services)** is a cloud platform provided by Amazon. It allows users to use **servers, storage, and networking services over the internet**. Instead of owning physical servers, resources can be created, used, and managed only when needed.

---

## Core AWS Concepts

### EC2 (Elastic Compute Cloud)

EC2 is a service that provides **virtual servers**, known as instances. These instances are used to run applications, websites, or backend services.

---

### Region

A **Region** is a physical location where AWS has its data centers. Each region is isolated from other regions.

---

### Availability Zone

An **Availability Zone (AZ)** is a data center within a region. Each region has multiple availability zones to provide **high availability and fault tolerance**.

---

### VPC (Virtual Private Cloud)

A **VPC** is a private virtual network inside AWS where resources such as EC2 instances are launched. It allows control over IP ranges, subnets, routing, and security, helping keep resources secure and isolated.

---

### Subnet

A **Subnet** is a smaller network inside a VPC.

* **Public Subnet**: Allows internet access
* **Private Subnet**: Used for internal resources

---

### Security Group

A **Security Group** acts as a firewall for EC2 instances. It controls **inbound and outbound traffic** using defined rules.

---

### IAM (Identity and Access Management)

**IAM** is used to manage users, roles, and permissions in AWS. It ensures that only authorized users and services can access AWS resources.

---

### Key Pair

A **Key Pair** is used to securely connect to an EC2 instance using SSH. It helps ensure secure access to the server.

---

## EC2 Creation Using AWS Console

The following steps were followed to create an EC2 instance manually:

1. Logged into the AWS Management Console
2. Navigated to the EC2 service
3. Clicked on **Launch Instance**
4. Selected **Amazon Linux** as the AMI
5. Chose **t3.micro** instance type
6. Created a new **Key Pair**
7. Configured a **Security Group** to allow SSH access
8. Launched the EC2 instance successfully

---

## EC2 Creation Using Terraform

The following steps were followed to create an EC2 instance using Terraform:

1. Installed Terraform on the local machine
2. Configured AWS CLI using `aws configure`
3. Created a folder for Terraform EC2 configuration
4. Wrote Terraform configuration in `main.tf`
5. Initialized Terraform
6. Created the EC2 instance using Terraform



