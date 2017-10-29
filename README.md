# Ansible playbook for Phabricator and Redmine Installation

To deploy redmine, run:
```
ansible-playbook playbooks/redmine.yml -i hosts/local.hosts
```
Plugins that are already inside the `plugins` folder will be automatically installed (make sure the folder name for each plugin is as-is, without any weird suffix)


To deploy phabricator, run:
```
ansible-playbook playbooks/phabricator.yml -i hosts/local.hosts
```

This example deploy to localhost on port 3000