# Enterprise-Workspace-Provisioner

# Enterprise Workspace Provisioner with Ansible

## Project Overview

Designed and implemented an automated server configuration solution using Ansible to standardize deployment environments across multiple Linux servers. The project demonstrates Configuration Management best practices by provisioning a consistent enterprise directory structure for application deployment, configuration management, and log storage across both staging and production environments.

Using Ansible's agentless architecture and YAML-based automation, the solution dynamically creates required directories with standardized permissions through a single reusable playbook. By leveraging inventory-driven configuration and loop-based task execution, the implementation reduces manual server setup effort, minimizes configuration drift, and improves deployment reliability.

## Responsibilities

* Developed Ansible playbooks to automate server provisioning tasks.
* Configured inventory-driven environment management for staging and production servers.
* Automated creation of enterprise-standard deployment directories.
* Implemented dynamic path generation using inventory variables.
* Applied secure file system permissions across all environments.
* Leveraged Ansible loops to eliminate repetitive configuration code.
* Executed automated infrastructure configuration across multiple servers simultaneously.

## Technologies Used

* Ansible
* YAML
* Linux Administration
* Configuration Management
* Infrastructure Automation

## Key Features

* Automated multi-server configuration management.
* Standardized directory provisioning across environments.
* Dynamic inventory-based path management.
* Secure directory permissions enforcement (0755).
* Agentless automation architecture.
* Reusable and scalable playbook design.
* Reduced manual server configuration effort.

## Business Value

This project demonstrates how Configuration Management can automate infrastructure setup and ensure consistency across environments. By standardizing deployment directories and permissions through code, organizations can reduce operational errors, accelerate application deployments, improve infrastructure reliability, and support scalable DevOps practices.

## Outcome

Successfully automated the provisioning of enterprise deployment directories across staging and production environments using Ansible, establishing a consistent and deployment-ready infrastructure foundation while reducing manual administration overhead.

## Run the Command

source .env/bin/activate
ansible-playbook main.yml

