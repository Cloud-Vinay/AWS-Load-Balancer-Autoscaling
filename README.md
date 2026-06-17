# AWS Load Balancer and Auto Scaling Project

## Project Overview

This project demonstrates a highly available AWS architecture using Amazon EC2, Application Load Balancer (ALB), and Auto Scaling Group (ASG).

The load balancer distributes incoming traffic across multiple EC2 instances, while Auto Scaling automatically replaces failed instances to maintain application availability.

## AWS Services Used

- Amazon EC2
- Application Load Balancer (ALB)
- Auto Scaling Group (ASG)
- Target Groups
- Security Groups
- Apache Web Server

## Project Implementation

### EC2 Setup
- Created multiple EC2 instances
- Installed Apache Web Server
- Hosted custom web pages

### Load Balancer Configuration
- Created Application Load Balancer
- Created Target Group
- Registered EC2 instances
- Verified traffic distribution

### Auto Scaling Configuration
- Created Launch Template
- Created Auto Scaling Group
- Desired Capacity: 2
- Minimum Capacity: 2
- Maximum Capacity: 4

### Auto Healing Test
- Terminated one EC2 instance manually
- Auto Scaling automatically launched a replacement instance

## Screenshots

### EC2 Instances Running
![EC2](01-ec2-instances-running.png)

### Server 1 Page
![Server1](02-server1-page.png)

### Server 2 Page
![Server2](03-server2-page.png)

### Target Group Healthy
![TargetGroup](04-target-group-healthy.png)

### Load Balancer Active
![ALB](05-load-balancer-active.png)

### ALB Working - Server 1
![ALB1](06-alb-working-server1.png)

### ALB Working - Server 2
![ALB2](07-alb-working-server2.png)

### Auto Scaling Group Overview
![ASG](08-autoscaling-group-overview.png)

### Auto Healing Test
![Healing](09-auto-healing-test.png)

## Skills Demonstrated

- AWS EC2
- Application Load Balancer
- Auto Scaling
- High Availability Architecture
- Linux Administration
- Apache Web Server
- AWS Networking
- Troubleshooting
