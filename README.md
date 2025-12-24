# Scalable PHP Web Application on AWS 🚀

This project demonstrates how to deploy a **scalable PHP web application on AWS** using **EC2, Application Load Balancer, and Auto Scaling Group**.  
The system automatically scales EC2 instances based on CPU load while maintaining a single public entry point.

---

## 🧩 Project Goal

Build a production-style cloud architecture where:

- Users access the application through **one public URL**
- Traffic is **automatically load balanced**
- EC2 instances **scale up and down based on CPU utilization**
- High availability is ensured using **multiple Availability Zones**
- Resources are cleaned up safely to avoid unnecessary cost

---

## 🔧 AWS Services Used

- Amazon EC2
- Application Load Balancer (ALB)
- Auto Scaling Group (ASG)
- Launch Template
- Amazon CloudWatch

---

## 🧱 Architecture Overview

User
↓
Application Load Balancer
↓
Target Group
↓
Auto Scaling Group (EC2 instances running PHP)
