# Ansible LAMP Stack for Ubuntu
A modular Ansible playbook designed to provesion and secure LAMP stack (Apache2, MySQL, PHP-FPM) on Ubuntu.

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

# Roadmap
[x] Basic modular playbook.
[x] Basic provesioning of LAMP stack (Apache2, MySQL, PHP-FPM).
[ ] Harden Apache2.
[ ] Harden MySQL.
[ ] Harden PHP-FPM.