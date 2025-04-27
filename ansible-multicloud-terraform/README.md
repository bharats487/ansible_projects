# Multi-Cloud Infrastructure Provisioning with Terraform and Ansible

Orchestrate Terraform with Ansible to provision resources in AWS, Azure, and GCP, then configure with Ansible.

## Features
- Terraform module orchestration
- Ansible dynamic inventory
- Cloud-init
- Cross-cloud networking
- Centralized logging

## Usage
- Edit `terraform/` modules and variables
- Run: `ansible-playbook -i inventory/terraform.py site.yml`

## Structure
- `site.yml`: Main playbook
- `terraform/`: Terraform modules
- `roles/`: app, monitoring, logging
