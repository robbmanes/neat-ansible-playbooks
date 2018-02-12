# miq-dev-playbook

An Ansible playbook for configuring a working development environment for [ManageIQ](http://manageiq.org/).

This playbook installs docker on the local host, and containerizes the database and key/value store so that the development host does not need to be affected.

## Usage
```
$ ansible-playbook -i inventory miq-dev-playbook.yml
```
