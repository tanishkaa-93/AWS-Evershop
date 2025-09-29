# AWS-Evershop
Deployment of Evershop using AWS

This repository contains a comprehensive, hands-on demonstration of a multi-tier web application deployment on AWS. It guides you through integrating core AWS services to build a scalable and secure infrastructure.

### Core AWS Services Implemented:
Compute: EC2 Instances
Database: RDS (MySQL) for a dedicated database lab
Storage & CDN: S3 for static assets, distributed via CloudFront
Scalability & High Availability: Auto Scaling Group (ASG) and Application Load Balancer (ALB)
DNS & Security: Route 53 for a custom domain with ACM providing HTTPS/TLS certificates
Application: EverShop (a Node.js e-commerce platform) deployed on EC2.

A detailed, step-by-step guide is provided in the accompanying PDF.

### Project Overview
Course: Learn To Deploy Real Time Website in AWS
Status: Complete (100%)
Modules Finished: 6 out of 6

### Completed Modules:
-✅ RDS MySQL Lab: Create a database and connect from an EC2 instance.
-✅ EverShop Deployment: Launch the Node.js e-commerce app on EC2.
-✅ S3 Integration: Configure a bucket for static product images.
-✅ Auto Scaling & Load Balancing: Set up an ASG behind an ALB.
-✅ Custom Domain & HTTPS: Use Route 53 and ACM for a secure, branded URL.
-✅ Content Delivery Network: Integrate CloudFront with S3 to optimize delivery and enhance security.

### Key Learning Outcomes
Through this project, you will gain practical experience in:
Architecting a highly available and scalable web application environment on AWS.
Implementing security best practices with HTTPS and restricted resource access.
Accelerating global content delivery using a CDN (CloudFront).
Managing application processes with PM2 and configuring web servers.

### Requirements
-An active AWS account
-Foundational understanding of AWS VPC, EC2, and Security Groups
-An SSH key pair for EC2 access
-A domain name (for the Route 53 and ACM module)

The EverShop application internally uses PostgreSQL.
These are distinct components designed to provide experience with different database technologies within a single project.
