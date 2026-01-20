# Ansible Home Lab Playbooks

Sample Ansible playbooks for **learning purposes**.  
Demonstrates managing users, SSH, services, templates, and basic web/database setup.

---

## Overview

- **User & SSH Management**
  - Add new users
  - Configure SSH access
  - Edit `sshd_config` via templates (`sshd_config_ansible1.j2`, `sshd_config_ubuntu.j2`)
  - Restart SSHD using handlers
  - Add SSH keys for users

- **Service & Configuration Management**
  - Edit configuration files (lineinfile, templates)
  - Manage services with handlers (start, restart)

- **Web & Database Setup**
  - Install `mariadb-server`
  - Install Apache2 + PHP
  - Copy default HTML files for a sample site
  - Configure basic webserver

- **Ansible Features Used**
  - Tasks
  - Handlers
  - Templates
  - Inventory management

---

## Notes
- This project is primarily for **learning purposes**
- Playbooks are **minimal** and demonstrate concepts, not production-ready configurations
