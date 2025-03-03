# aws-terraform-ansible-setup

# 🚀 AWS Terraform & Ansible Setup

This project automates the deployment of AWS infrastructure using **Terraform** and configures it using **Ansible**.

## 📌 Features
- ✅ Terraform for AWS infrastructure provisioning
- ✅ Ansible for automated configuration
- ✅ Deploys EC2 instances with security groups
- ✅ Supports variable configurations

## 🛠️ Prerequisites
- Install **Terraform**: [Download](https://developer.hashicorp.com/terraform/downloads)
- Install **Ansible**: `sudo apt install ansible -y`
- Configure **AWS CLI**: `aws configure`

## 🚀 Setup & Deployment

1️⃣ **Clone this repo:**
```bash
git clone https://github.com/Rohan040201/aws-terraform-ansible-setup.git

cd aws-terraform-ansible-setup

2️⃣ Initialize Terraform
terraform init

3️⃣ Deploy Infrastructure
terraform apply -auto-approve

4️⃣ Run Ansible Playbook
ansible-playbook -i inventory playbook.yml
