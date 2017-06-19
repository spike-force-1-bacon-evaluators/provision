# Provision

## Ansible Control Node

Install control node on DigitalOcean instance:
```
git clone git@github.com:spike-force-1-bacon-evaluators/provision.git
ansible-playbook playbooks/controller.yml -i playbooks/roles/ansible/files/.inventory -K
```

Get playbooks:
```
ssh ansible@IP
git clone https://github.com/spike-force-1-bacon-evaluators/playbooks.git
```

Install Jenkins:
```
ssh ansible@IP
ansible-playbook playbooks/jenkins.yml -K
```
Tested version: `ansible 2.2.1.0`

## [Documentation](https://github.com/spike-force-1-bacon-evaluators/documentation/blob/master/README.md)

### [Ways of Working](https://github.com/spike-force-1-bacon-evaluators/documentation/blob/master/docs/ways-of-working.md)
