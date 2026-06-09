# Salt Minion Onboarding

## Overview

Ansible playbook for automating Salt Minion installation, configuration, registration, and service management.

## Features

* Salt Minion installation
* Salt Master configuration
* Automatic Minion ID assignment
* Service enablement
* Configuration standardization

## Use Case

Used to onboard Linux servers into Salt-managed infrastructure while ensuring consistent configuration across environments.

## Requirements

* Ansible 2.12+
* Debian/Ubuntu target hosts
* Reachability to Salt Master

## Usage

```bash
ansible-playbook ansible-salt-minion-onboarding.yml
```

## Inventory Example

```ini
server01.example.com ansible_host=192.0.2.10
server02.example.com ansible_host=192.0.2.11
```

The inventory hostname is used as the Salt Minion ID.

## Skills Demonstrated

* SaltStack
* Configuration Management
* Linux Administration
* Infrastructure Automation
* Ansible
