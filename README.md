# Ansible Tutorial Examples

This `ansible_tutorial` repository contains the sample Ansible playbooks used in the
[Nebulon Ansible](https://on.nebulon.com/docs/en-us/tutorials/tutorial-ansible/8041667baadd168c8333f3aa991637c1)
tutorial available at <https://on.nebulon.com/docs>. These example playbooks are for educational
and instructional use only and are provided as-is. Please see the tutorial for further details.

## Prerequisites

- `nebpyclient` version 2.0.8
- `nebulon_on` Ansible module version 1.3.1
- Ansible 3.0 (Ansible Core 2.10) or later
- Python 3.6 or later

## File structure

The repository contains the following file structure:

```shell
├── .vault_pass         # Ansible Vault password - Excluded from repo, you must create this file 
├── README.md
├── ansible.cfg         # project specific ansible configuration file
├── inventory           # this directory contains an example inventory
│   └── servers.ini     # Ansible inventory file used in example playbooks
└── playbooks           # Example playbooks in this directory 
    ├── host_information.yml
    ├── managing_users_and_groups.yml
    ├── managing_volumes.yml
    ├── neb_data_protection.yml
    ├── npod_management.yml
    ├── set_ntp.yml
    ├── vars_files      # Playbook specific variable files
    │   ├── credentials.yml # Ansible Vault - Excluded from repo, you must create this file 
    │   ├── host_information_vars.yml
    │   ├── managing_users_and_groups_vars.yml
    │   ├── managing_volumes_vars.yml
    │   ├── neb_data_protection_vars.yml
    │   ├── npod_management_vars.yml
    │   ├── set_ntp_vars.yml
    │   └── working_with_inventory_vars.yml
    └── working_with_inventory.yml
```
