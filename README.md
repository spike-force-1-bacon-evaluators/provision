# Provision

## Ansible Control Node

Install control node on DigitalOcean instance.

```
git clone git@github.com:spike-force-1-bacon-evaluators/provision.git
ansible-playbook playbooks/controller.yml -i playbooks/roles/ansible/files/.inventory --ask-become-pass -vv
```

Ansible version: `2.2.1.0`
