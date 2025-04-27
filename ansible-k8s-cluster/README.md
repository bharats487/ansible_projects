# Kubernetes Cluster Deployment and Management

This project automates the provisioning and lifecycle management of a highly available Kubernetes cluster using Ansible.

## Features
- Multi-master and worker node setup
- Etcd cluster configuration
- Networking (CNI plugins)
- Monitoring (Prometheus)
- Add-ons (Helm, Ingress)
- Rolling upgrades

## Usage
- Edit `inventory/hosts.ini` with your node IPs
- Run: `ansible-playbook -i inventory/hosts.ini site.yml`

## Structure
- `site.yml`: Entry playbook
- `roles/`: Contains roles for k8s, etcd, docker, networking, monitoring
