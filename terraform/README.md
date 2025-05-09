# Terraform: Infrastructure definition

```
terraform/
    ├── modules/            # Reusable Terraform modules
    ├── environments/       # Environment-specific configuration (dev, prod)
    │   ├── dev.tfvars
    │   └── prod.tfvars
    ├── main.tf             # General definition of the infrastructure
    ├── variables.tf        # Global Terraform variables
    ├── outputs.tf          # Definition of relevant outputs
    ├── backend.tf          # Backend configuration for remote state
    ├── (terraform.tfstate) # State file (should not be versioned)
    └── README.md           # Documentation on how to use Terraform
```