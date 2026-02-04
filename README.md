🚀 AWS EC2 Provisioning Using Terraform

This project demonstrates how to provision an AWS EC2 instance using Terraform with secure SSH key-based access and automated instance initialization.

All infrastructure is managed using Infrastructure as Code (IaC) principles.

## 📌 Features

-  EC2 instance creation using Terraform  
-  SSH key authentication (no passwords)  
-  Automated setup using user-data scripts  
-  Secure handling of Terraform state files  
-  GitHub-based infrastructure versioning  


🛠️ Tech Stack
Tool	Purpose
Terraform	Infrastructure provisioning
AWS EC2	Cloud compute instance
SSH Keys	Secure authentication
GitHub	Version control

<img width="803" height="290" alt="image" src="https://github.com/user-attachments/assets/b2c67f1a-3460-4b35-869f-299a6ae3e5e0" />

🚀 How to Deploy
1️⃣ Configure AWS Credentials
   - aws configure

2️⃣ Initialize Terraform
   - terraform init

3️⃣ Preview Infrastructure
   - terraform plan

4️⃣ Create EC2 Instance
   - terraform apply

5️⃣ Connect via SSH
   -  ssh -i your-key.pem ubuntu@<EC2_PUBLIC_IP>

Terraform project to provision AWS EC2 using SSH authentication & automated scripts


