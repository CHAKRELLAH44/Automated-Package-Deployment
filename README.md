#  Automated Package Deployment with Ansible

##  Overview
This mini-project demonstrates how to automate the installation of a software package (such as **Nginx**) across multiple servers using **Ansible**.  
Instead of installing the package manually on each machine, Ansible executes a **single playbook** that applies the same task to all target servers via SSH.

This project highlights key DevOps principles:
- Infrastructure as Code (IaC)
- Automation & repeatability
- Multi-server orchestration

---

##  Project Goal
Deploy a package simultaneously on several servers by running a single Ansible playbook.

Example:  
Automatically install **Nginx** on 2 or 3 Ubuntu machines.

---



##  Project Structure
mini_projet_ansible/<br>
│── hosts.ini<br>
│── install_nginx.yml<br>
│── README.md



##  Running the Project
ansible-playbook -i hosts.ini install_nginx.yml

Result:
✔ Nginx installed automatically on all target servers
✔ One command → multiple deployments
