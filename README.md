# Aalto-2022-infra

## Installing

Install Ansible for your system first.

```
$ ansible-galaxy install -r requirements.yml
$ ansible-playbook playbook.yml -v -u root -i hosts --private-key=~/.ssh/bytecraft-hetzner
```
