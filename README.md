# Terraform AWS VPC and EC2 Setup

This repository contains the Terraform configuration for setting up an AWS VPC and EC2 instances.

## Prerequisites
1. Install [Git](https://git-scm.com/).
2. Install [Terraform](https://www.terraform.io/downloads.html).
3. Set up an AWS account and configure AWS CLI.

## Setup and Push to GitHub

1. Initialize Git Repository

git init


2. Clone the Repository

git clone https://github.com/sushu126/terraform-aws-vpc-ec2.git
cd terraform-aws-vpc-ec2


3. Set Git User Identity

git config --global user.name "Your Name"
git config --global user.email "your-email@example.com"


4. Add Files to Git

git add .

terraform-aws-vpc-ec2
│── main.tf               # Terraform provider and VPC setup
│── network.tf            # Subnets, Internet Gateway, NAT, Route Tables
│── ec2.tf                # EC2 instance and security groups
│── variables.tf          # Variables for flexibility
│── outputs.tf            # Outputs for deployed resources


5. Commit Changes

git commit -m "any comments"


6. Add Remote Repository

git remote add origin https://github.com/sushu126/terraform-aws-vpc-ec2.git


7. Push to GitHub

git branch -M main
git push -u origin main


8. Open Project in VS Code

cd terraform-aws-vpc-ec2
