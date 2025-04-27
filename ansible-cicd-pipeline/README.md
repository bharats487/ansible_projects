# CI/CD Pipeline Setup with Jenkins

Automate deployment of Jenkins, configure jobs, install plugins, manage credentials, set up webhooks.

## Features
- Jenkins master/agent setup
- Plugin management
- Job DSL
- Secure credentials
- Backup/restore

## Usage
- Edit `inventory/hosts.ini`
- Run: `ansible-playbook -i inventory/hosts.ini site.yml`

## Structure
- `site.yml`: Main playbook
- `roles/`: jenkins, jobs, plugins, credentials
