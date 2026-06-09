# Ubuntu Repository Standardization

## Overview

Ansible playbook for standardizing Ubuntu package repositories and automating repository migration activities.

## Features

* Backs up existing repository configuration
* Replaces legacy repository definitions
* Configures approved package repositories
* Archives deprecated repository files
* Refreshes package metadata

## Use Case

Used to migrate Linux servers to standardized repository sources and improve package governance across environments.

## Requirements

* Ansible 2.12+
* Ubuntu target hosts

## Usage

```bash
ansible-playbook ansible-ubuntu-repository-standardization.yml
```

## Skills Demonstrated

* APT Repository Management
* Linux Administration
* Change Management
* Configuration Standardization
* Ansible
