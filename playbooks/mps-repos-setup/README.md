# mps-repos-setup
ansible playbook for configuring managed platform github repositories

## Usage
Change the `mps_path` variable to reflect where you want your repositories to be cloned:
```
mps_path: /home/rmanes/Source/mps-repos
```

Run the playbook:
```
$ ansible-playbook -i inventory mps-repos-setup.yml
```
