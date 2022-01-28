## Create Resource Dependencies
In this tutorial, you will learn about dependencies between resources and modules. Most of the time, Terraform infers dependencies between resources based on the configuration given, so that resources are created and destroyed in the correct order. Occasionally, however, Terraform cannot infer dependencies between different pargts of your infrastructure, and you will need to create an explicit dependency with the `depends_on` argument.

### Manage implicit dependencies
- Paste the configuration into a file named `main.tf`.
- `terraform init`
- `terraform apply`

### Manage explicit dependencies
Implicit dependencies are the primary way that Terraform understands the relationships between your resources. Sometimes there are dependencies between resources that are not visible to Terraform, however. The `depends_on` argument is accepted by any resource or module block and accepts a list of resources to create explicit dependencies for.
- Add the following config to `main.tf`.
- Run `terraform get` to install the module.

<img width="774" alt="Screen Shot 2565-01-28 at 08 14 08" src="https://user-images.githubusercontent.com/33342822/151469763-6d88cea2-edaa-407e-bf95-ad7bb612ab3e.png">

### Reference
https://learn.hashicorp.com/tutorials/terraform/dependencies
