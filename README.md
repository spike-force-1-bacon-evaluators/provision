# Provision

## Ansible Control Node

Install control node on DigitalOcean instance:
```
git clone git@github.com:spike-force-1-bacon-evaluators/provision.git
ansible-playbook playbooks/controller.yml -i playbooks/roles/ansible/files/.inventory -K
```

Get playbooks:
```
ssh ansible@138.68.145.244
git clone https://github.com/spike-force-1-bacon-evaluators/playbooks.git
```

Install Jenkins:
```
ssh ansible@138.68.145.244
ansible-playbook playbooks/jenkins.yml -K
```
Tested version: `ansible 2.2.1.0`
