# CIFS Share Provisioning

## Overview

Ansible playbook for automating CIFS share provisioning and persistent filesystem configuration on Linux servers.

## Features

* Installs required CIFS packages
* Creates mount point directories
* Configures persistent mounts
* Supports multiple CIFS shares
* Automatically mounts filesystems

## Use Case

Used to standardize access to centralized configuration and certificate repositories across large Linux server environments.

## Requirements

* Ansible 2.12+
* Linux target hosts
* Accessible CIFS/SMB server

## Usage

```bash
ansible-playbook ansible-cifs-share-provisioning.yml
```

## Skills Demonstrated

* Ansible
* Linux Administration
* CIFS / SMB
* Infrastructure as Code
* Filesystem Management
