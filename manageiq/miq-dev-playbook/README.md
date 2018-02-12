# miq-dev-playbook

An Ansible playbook for configuring a working development environment for [ManageIQ](http://manageiq.org/).  It currently only supports Fedora 25 and above, with plans to expand.

This playbook installs docker on the local host, and containerizes the database and key/value store so that the development host does not need to be affected.

## Usage
Change the `miq_path` variable to reflect where you want your repositories to be cloned:
```
miq_path: /home/rmanes/my_source_directory/ManageIQ
```

Run the playbook:
```
$ ansible-playbook -i inventory miq-dev-playbook.yml
```
