# # AWS Budget Terraform Project

This Terraform project creates an `AWS Budget` resource to monitor and control monthly spending in your AWS account.

## Prerequisites

- Terraform Infrasture as Code (IAC)
- An AWS account with proper IAM permissions
- AWS CLI configured with access keys or credentials

## Configuration

The Terraform configuration specifies:

- **Provider:** AWS (`eu-central-1` region)
- **Budget:** Monthly cost budget of **$500 USD**
