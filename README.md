# Ansible LAMP Stack for Ubuntu
A modular Ansible playbook designed to provision a LAMP stack (Apache2, MySQL, PHP-FPM) on Ubuntu server.

# Environment
- Ansible: core 2.19.0
- Target System: Ubuntu 25.10
- SSH Access: root

# Configuration
Update `hosts` with your server(s) details.

# Usage
1. Install requirements.

```bash
ansible-galaxy install -r requirements.yml
```
2. Execute the playbook.

```bash
ansible-playbook -i hosts playbook.yml
```
