# useful-terraform

Examples of clean and scalable Terraform project structures, modules, and automation practices.

## Purpose

This repository was created to share a practical and organized way to structure Terraform code. 

It's main goal is to make it easier to set up workflows and pipelines, help teams automate more efficiently, and keep the project easy to understand and maintain over time.

After seeing a lot of poorly organized Terraform code in the past, I wanted to build something that shows a clearer and better approach. 

This structure is meant to help both developers and DevOps teams collaborate more easily when working with Infrastructure as Code.

The layout here follows the Gruntwork style, which is a proven and effective way to separate reusable modules from environment-specific configurations.

## Project Layout

- **infrastructure-modules/**: Reusable Terraform modules, like VPC, ECS, and ALB.
- **infrastructure-live/**: Environment-specific configurations for dev, prod, and others.
- **.github/workflows/**: Sample automation workflows for planning, applying, and scanning Terraform code.

This setup is meant to be simple, practical, and ready for real-world use.

## Highlights

- Clear separation between reusable modules and live configurations
- Easy to add new modules, update infrastructure, and manage versions
- Sample CI workflows for formatting, validating, planning, applying, and basic security scanning
- Inspired by lessons learned in real projects and based on Gruntwork best practices

## Technologies Used

- Terraform 1.5+
- Terragrunt
- GitHub Actions

## Notes

This is a growing project and will continue to evolve as new ideas and improvements are added.
