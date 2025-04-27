# Enterprise Windows Server Automation

Automate Windows infrastructure: AD domain join, GPO, IIS setup, patching, user management.

## Features
- WinRM setup
- Domain join
- User/group management
- IIS configuration
- Security policies

## Usage
- Edit `inventory/hosts.ini` with Windows hosts
- Run: `ansible-playbook -i inventory/hosts.ini site.yml`

## Structure
- `site.yml`: Main playbook
- `roles/`: winrm, domain, users, iis, gpo
