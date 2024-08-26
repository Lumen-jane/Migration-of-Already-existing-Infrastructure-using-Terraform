# Migration-of-Already-existing-Infrastructure-using-Terraform
Importing CloudFormation Configuration to Terraform

Migrating from CloudFormation to Terraform involves transitioning infrastructure management while retaining existing resources. The process typically includes:

Export CloudFormation Resources: Identify and export the resource IDs managed by CloudFormation.
Create Terraform Configuration: Write the equivalent Terraform configuration files for those resources.
Use the terraform import Command: Import the existing resources into the Terraform state using the terraform import command. This associates the existing infrastructure with your Terraform configurations.
Verify and Plan: Run terraform plan to verify that the imported resources match the desired configuration without changes.
Manage with Terraform: Continue managing your infrastructure with Terraform, ensuring all changes are tracked and versioned within Terraform.
This method allows you to smoothly transition from CloudFormation to Terraform while maintaining infrastructure continuity.
