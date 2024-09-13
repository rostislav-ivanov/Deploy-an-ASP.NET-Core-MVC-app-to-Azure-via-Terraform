Deploy an ASP.NET Core MVC app to Azure via Terraform.

You need to have an Azure account and to have installed Azure CLI local.

You are provided with a .NET application that consists of two projects – one for the web application and one for the SQL Server database. 

## Deploy the app using four Terraform configuration files – main.tf, variables.tf, values.tfvars, outputs.tf. 
- clone this project localy
- open "terraform" folder by terminal
- run commands:
  - az login
  - terraform init
  - terraform apply -var-file="values.tfvars" -auto-approve
## Destroy the app using four Terraform configuration files – main.tf, variables.tf, values.tfvars, outputs.tf. 
- terraform destroy -var-file="values.tfvars" -auto-approve
