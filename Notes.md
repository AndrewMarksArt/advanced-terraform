# Terraform Review
### Terms:
1. **Configuration** -> an independently deployable collection of Hashicorp Configuration Language files -- defines resources, variables, and values and a single configuration is a collection of several files.

2. **HashiCorp Configuration Language (HCL)** -> a domain-specific language, developed by HashiCorp, used to describe a Terraform configuration -- created because YAML and JSON lacked the features to make Terraform as adaptable as it needed to be.

3. **Resource** -> a generic term for anything that can be created in a cloud or other Terraform-compatible system -- Terraform is generally used to create instances of 'something' in a cloud or provider.

4. **Deployment** -> the set of resources created by a Terraform configuration.

5. **Provider** -> a cloud or system-specific Terraform plugin that supports resource creation for that system.

6. **Module** -> an isolated, reusable sub-configuration