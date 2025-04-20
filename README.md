# Ansible Basic Server Setup

This playbook configures a basic Ubuntu 22.04 server with:

- System updates
- NGINX web server
- UFW firewall
- Fail2ban
- Basic system tools (htop, etc.)
- Simple welcome page

## ✅ Prerequisites

- Control node (your local machine or VM) with Ansible installed
- Remote Ubuntu 22.04 server with SSH access
- SSH key configured

## 🚀 Usage

1. Clone the repo:
   ```bash
   git clone https://github.com/InfraFort/ansible-basic-server-setup.git
   cd ansible-basic-server-setup

2. Edit inventory and replace your.server.ip.here with your server IP

3.
   ```bash
   ansible-playbook -i inventory playbook.yml --ask-become-pass