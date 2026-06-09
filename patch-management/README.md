# Ubuntu Patch Management

## Overview

Ansible playbook for automating Ubuntu patch management while protecting critical infrastructure services from unintended upgrades.

## Features

* Updates package metadata
* Applies operating system patches
* Holds protected packages
* Detects reboot requirements
* Performs cleanup of obsolete packages

## Protected Services

Examples include:

* Docker
* RabbitMQ
* Redis
* PostgreSQL
* MySQL
* Elasticsearch
* Salt Minion

## Use Case

Designed to standardize patch management workflows across large Linux server fleets while reducing operational risk.

## Requirements

* Ansible 2.12+
* Ubuntu target hosts

## Usage

```bash
ansible-playbook ansible-ubuntu-patch-management.yml
```

## Skills Demonstrated

* Patch Management
* Linux Administration
* Change Management
* Fleet Operations
* Ansible
