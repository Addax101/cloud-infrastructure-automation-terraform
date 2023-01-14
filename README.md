# cloud-infrastructure-automation-terraform
This repository contains the code and scripts for automating the provisioning and management of cloud infrastructure using Terraform.

## Getting Started
These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

## prerequisites
* Terraform
* AWS or Azure or GCP account
* Basic understanding of cloud infrastructure and services
## Installing
* Clone the repository: `git clone https://github.com/Addax101/cloud-infrastructure-automation-terraform.git`
* Create a `terraform.tfvars` file in the root of the repository and add your cloud provider's credentials.

* Install the required provider plugin by running `terraform init`

* Provision the infrastructure by running `terraform apply`
* To make changes to the infrastructure, edit the `.tf` files, and run `terraform apply` again.
* To destroy the infrastructure, run `terraform destroy`

## Examples
This repository contains examples of how to use Terraform to automate the following:

* Creating a Virtual Machine
* Creating a Load Balancer
* Creating a Database

## Note
* Make sure to store your state file in a secure location such as Terraform Cloud or AWS S3
* Be careful when running terraform destroy, as it will delete all the resources created by Terraform.
## Built With
* Terraform - Infrastructure as Code Tool
* AWS/Azure/GCP - Cloud Providers

## Authors
 
## License
This project is licensed under the MIT License - see the LICENSE.md file for details.

## Acknowledgments
GPS
