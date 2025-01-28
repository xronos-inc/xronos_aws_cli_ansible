# aws-cli Ansible role

Install AWS-CLI on a host.

## Requirements

Provisioning host:

- ansible 2.15 or later

Host that will run AWS CLI

- Ubuntu 22.04 or 24.04

## How to use this role

```yaml
- name: install AWS CLI
  role: xronos_aws_cli_ansible
```

### Variables

- `aws_cli_version`: version number of the AWS CLI to install. Leave empty for the lastest.
