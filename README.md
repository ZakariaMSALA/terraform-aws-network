# 🌐 Terraform AWS VPC

This repository contains a basic infrastructure setup using Terraform to provision a VPC on AWS.

## 🧱 Files
- `main.tf` – infrastructure definition
- `variables.tf` – configurable inputs
- `outputs.tf` – exported outputs (VPC ID)

## 🚀 How to Use

Make sure you have your AWS credentials exported:

```bash
export AWS_ACCESS_KEY_ID=your_access_key
export AWS_SECRET_ACCESS_KEY=your_secret_key
```

Then run:

```bash
terraform init
terraform plan
terraform apply
```

## 🔧 Customization

Edit `variables.tf` or pass values using a `terraform.tfvars` file to customize the region or CIDR block.

## 📬 Author

Zakaria Msala – Freelance DevOps Engineer  
[LinkedIn](https://linkedin.com/in/zakaria-msala)
