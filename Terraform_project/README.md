# 🎯 Creating an EC2_Instance using Terraform
## ✅ Step 1: Install Required Tools
# Install Terraform
Download from terraform.io/downloads and add it to our system PATH.

## To confirm installation:
terraform -version
![terraform-install](https://github.com/user-attachments/assets/9b3a8925-e45f-469c-8ae0-e2d475b10b9b)


## Install AWS CLI
Then configure your credentials:
aws configure

## 📄 Step 2: Create the Terraform Files in VS Code
main.tf 
![terraform-main](https://github.com/user-attachments/assets/b6d72c84-7f49-49a6-a46b-2a5f11850e80)

variables.tf
![terraform-variables](https://github.com/user-attachments/assets/671c0d26-42ad-4267-a8e6-2564feb75cda)

output.tf
![terraform-output](https://github.com/user-attachments/assets/30caffcc-c2a2-450c-836e-d45cbd6a864e)

## 🔄 Step 3: Initialize and Apply
terraform init
![terraform-init](https://github.com/user-attachments/assets/7f18ebd7-afb2-421c-abd8-d817d65a267b)

terraform plan
![terraform-plan](https://github.com/user-attachments/assets/7e4a8697-a7c5-44ac-94fe-d904c3fba7a4)

terraform apply
![terraform-apply](https://github.com/user-attachments/assets/95aa2bc3-a1d1-4049-b9f9-0d9d3cac66fa)

## 📍 Step 4: Verify
in cmd
![terraform-success](https://github.com/user-attachments/assets/f4449dec-8119-4479-b940-af02701c62d1)

in AWS_EC2
![terraform-aws-verify](https://github.com/user-attachments/assets/bfbda19d-e08a-4b0a-a380-b50aa22e5485)

## 🧼 Step 5: Clean Up (Avoid Charges)

terraform destroy

