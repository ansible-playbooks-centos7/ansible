[![](https://github.com/ansible-playbooks-centos7/ansible/workflows/build/badge.svg)](https://github.com/ansible-playbooks-centos7/ansible/actions?query=workflow%3Abuild)

# Ansible Playbook - Ansible

## Introduction

This program installs [Ansible](https://github.com/ansible/ansible) on CentOS7.

## How To install

1. Install Ansible and git

```
sudo yum -y install epel-release git
sudo yum -y install ansible
```

2. Execute playbook as root

```
git clone https://github.com/ansible-playbooks-centos7/ansible.git
cd ansible
ansible-galaxy install -r roles/requirements.yml -p roles/
ansible-playbook -i localhost, -c local install.yml
```
