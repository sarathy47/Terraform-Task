# Terraform-Task
# Terraform - Launch Linux EC2 Instances in Two AWS Regions

## 📌 Project Overview

This project demonstrates how to use **Terraform** and the **AWS CLI** to provision Linux EC2 instances across multiple AWS regions using a single Terraform configuration file.

The project uses:

- AWS EC2
- Terraform
- AWS CLI
- AWS CloudShell
- GitHub

## 🎯 Objective

The objective of this task is to:

1. Configure Terraform for AWS.
2. Use a single `main.tf` file.
3. Configure AWS providers for two different regions.
4. Create Linux EC2 instances using Terraform.
5. Validate and plan the infrastructure using Terraform.
6. Verify the deployed EC2 instance using AWS CLI.
7. Maintain the Terraform code and execution screenshots in GitHub.

---

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| AWS EC2 | Virtual machine infrastructure |
| Terraform | Infrastructure as Code |
| AWS CLI | AWS resource verification |
| AWS CloudShell | Execution environment |
| GitHub | Source code and screenshot submission |

---

## 📁 Project Structure

```text
terraform-two-region-ec2/
│
├── main.tf
├── README.md
│
└── screenshots/
    ├── 01-mumbai-ami.png
    ├── 02-terraform-init.png
    ├── 03-terraform-validate.png
    ├── 04-cloudshell-terraform-version.png
    ├── 05-cloudshell-terraform-init.png
    ├── 06-terraform-validate.png
    ├── 07-terraform-plan.png
    ├── 08-terraform-apply.png
    └── 09-mumbai-ec2-running.png
