# 🚀 S3 Static Website Hosting with Terraform

## 📌 Project Overview
This project demonstrates how to **automate static website hosting** using **AWS S3 and Terraform**. The setup provisions an **AWS S3 bucket** with static website hosting, defines proper bucket policies, and ensures **secure and public accessibility**. With **Terraform**, you can **deploy, update, and manage your static website** effortlessly.

## 🌟 Features
- ✅ **Automated Deployment** – Run `terraform apply` to provision the entire infrastructure.
- ✅ **Static Website Hosting on AWS S3** – No need for traditional web servers.
- ✅ **Custom Bucket Policies & Secure Access Control.**
- ✅ **Easy Updates** – Modify `index.html`, run Terraform, and reflect changes instantly.
- ✅ **Supports Public Access (With Configurable Security).**
- ✅ **Scalable, Cost-Effective, and Serverless Hosting.**

## 🛠 Tech Stack
- **Terraform** – Infrastructure as Code (IaC) for AWS resource provisioning.
- **AWS S3** – Storage & static website hosting.
- **AWS IAM** – Secure access control.
- **AWS CloudFront** *(Optional)* – CDN for better performance.
- **AWS Route 53** *(Optional)* – Custom domain support.

## 📂 Project Structure
📁 terraform-s3-static-website/ │── 📄 main.tf # Terraform configuration for S3, IAM & hosting │── 📄 variables.tf # Configurable variables │── 📄 outputs.tf # Terraform outputs (website URL) │── 📄 index.html # Sample homepage content │── 📄 error.html # Custom error page │── 📄 README.md # Project documentation




