## Create Resource Dependencies
In this tutorial, you will learn about dependencies between resources and modules. Most of the time, Terraform infers dependencies between resources based on the configuration given, so that resources are created and destroyed in the correct order. Occasionally, however, Terraform cannot infer dependencies between different pargts of your infrastructure, and you will need to create an explicit dependency with the `depends_on` argument.

### Manage implicit dependencies
- Paste the configuration into a file named `main.tf`.
- `terraform init`
- `terraform apply`

### Reference
https://learn.hashicorp.com/tutorials/terraform/dependencies