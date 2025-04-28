# playbook
Ansible playbook to setup local environment

OS X:
```bash
$ ansible-playbook ~/playbook/local_setup.yml -i ~/playbook/localhost.inv
```

OpenSUSE:
```bash
ansible-playbook ~/playbook/local_opensuse.yml -i ~/playbook/opensuse.inv --ask-become
```
