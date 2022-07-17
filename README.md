# os-hardening

## Pre-requisites

- Ansible must be installed

# How to run

- Edit the `hosts.yaml` to point to your hosts
- Edit the "sudo" password and user: `ansible-vault edit group_vars/all/vault`
- Run the hardening script: `make harden`
