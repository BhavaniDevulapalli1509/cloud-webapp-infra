# cloud-webapp-infra

Cloud Web Application with Infrastructure as Code

This repository contains a cloud-native web application along with its supporting infrastructure. The project is designed using microservices, containerization, and Infrastructure as Code (IaC) principles to enable scalability, high availability, and secure deployments on cloud platforms such as AWS.

🚀 Project Overview

Web Application: A Node.js-based RESTful API with CI/CD workflows, automated builds, and containerized deployment.

Infrastructure as Code: Provisioning and management of AWS cloud resources using Terraform and Packer.

CI/CD: GitHub Actions workflows for testing, building, and deploying both infrastructure and application.


🛠️ Components
Web Application

Built with Node.js + Express.js

REST API endpoints for user operations

CI/CD pipeline for automated builds and deployments

Testing framework integrated (Jest, Postman)

Infrastructure (Terraform + Packer)

Compute: EC2 instances with AMI builds via Packer

Database: RDS (PostgreSQL) configuration

Networking: VPC, subnets, security groups, routing

Storage: S3 bucket configurations with policies and encryption

Monitoring: CloudWatch alarms, metrics, and log groups

IAM: Roles and policies for EC2, Lambda, and services

Scaling: Auto Scaling Groups and Load Balancer setup
