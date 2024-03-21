# aws-cli Ansible role

Install AWS-CLI on a host, and use AWS-CLI in Ansible roles

This role derives from [creatoreng/creator-aws-cli-ansible](https://github.com/creatoreng/creator-aws-cli-ansible).

## Requirements

Provisioning host:

- ansible 2.15 or later

Host that will run AWS CLI

- Ubuntu 22.04 or later (or equivalentr Debian-based Linux distro running apt)

## How to use this role

```yaml
- name: install AWS CLI
  role: xronos_aws_cli_ansible
```
