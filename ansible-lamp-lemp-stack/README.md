# LAMP/LEMP Stack Deployment

Automate deployment of a scalable LAMP/LEMP stack (Linux, Apache/Nginx, MySQL/MariaDB, PHP) with SSL and app deployment.

## Features
- Idempotent roles for each component
- Database hardening
- Application deployment (WordPress)
- Let's Encrypt SSL

## Usage
- Edit `inventory/hosts.ini`
- Run: `ansible-playbook -i inventory/hosts.ini site.yml`

## Structure
- `site.yml`: Main playbook
- `roles/`: Apache/Nginx, MySQL/MariaDB, PHP, app, ssl
