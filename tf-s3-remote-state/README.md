# Migrate State from S3 to Terraform Cloud

This is a companion repository to the [Migrate from Remote S3 Backend to Terraform Cloud](https://developer.hashicorp.com/terraform/tutorials/cloud/migrate-remote-s3-backend-tfc) tutorial.

This repository creates the S3 bucket and DynamoDB table to set up S3 remote backend.

Chnage name for dynamedb table on main.tf line 24 just change the #5 to a different number everytime you create a new backend 

```sh 
terraform init
terraform fmt 
terraform validate 
terraform plan 
terraform apply -auto-approve




```