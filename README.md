# Todo Configuration Management

Todo Configuration Management is used to config services. It's based on Ansible code.

## Table of contents

- [How to use](#how-to-use)
- [Development scripts](#development-scripts)
- [Important notes](#important-notes)

## How to use

1. Clone this repo
2. Install Ansible CLI
3. For the `ansible-vault` password please contact the repository owner or the person responsible for this repository to obtain them

## Development scripts

This template provides a handful of scripts to make your dev experience better!

- Encrypt sensitive data
  - `ansible-vault encrypt_string`
- Run playbook
  - `ansible-playbook --ask-vault-password playbook.yaml`

## Important notes

- Must encrypt sensitive data with command `ansible-vault` for making sure that data will be not readable
