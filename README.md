# Azure Cloud Security Lab

A hands-on learning project focused on deploying, securing, monitoring, and automating a small application environment in Microsoft Azure.

## Project goal

Build a working environment and demonstrate practical skills in Linux administration, networking, identity and access management, monitoring, and infrastructure as code.

The application will be a simple IT ticket tracker using test data.

## Current status

Project setup in progress. An Azure account and an active subscription have been confirmed. Infrastructure deployment and security testing are planned.

## Project roadmap

- [ ] Configure a budget and cost alerts.
- [ ] Create a resource group and resource tags.
- [ ] Configure a virtual network, subnet, and Network Security Group.
- [ ] Deploy an Ubuntu virtual machine with SSH key authentication.
- [ ] Restrict administrative access to an approved IP address.
- [ ] Deploy the ticket tracker application.
- [ ] Configure HTTPS and application service permissions.
- [ ] Configure Managed Identity and Azure Key Vault access.
- [ ] Collect selected logs and configure an alert.
- [ ] Test access controls and document the results.
- [ ] Simulate and investigate a controlled incident.
- [ ] Recreate the infrastructure using Terraform.
- [ ] Document deployment, cleanup, costs, and lessons learned.

## Planned technologies

Microsoft Azure, Ubuntu Linux, Python, Git, Terraform, Azure Key Vault, Managed Identity, Azure RBAC, and Azure Monitor.

## Documentation

Documentation will include:

- An architecture diagram and design decisions.
- Deployment and cleanup instructions.
- Security tests with expected and actual results.
- Troubleshooting notes and lessons learned.
- A summary of resource costs.

## Lab scope

This is a learning environment using test data. It is not a production deployment.

Credentials, private SSH keys, secrets, and Terraform state files must not be committed to this repository.
