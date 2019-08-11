This playbook installs Ansible on CentOS7.

## Install Ansible

Change to root and execute commands below.

```
ansible-galaxy install -r roles/requirements.yml
ansible-playbook -i localhost, -c local install.yml
```


