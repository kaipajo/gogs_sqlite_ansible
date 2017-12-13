# Gogs ansible installation

- Inventory file contains all host related information. Currently using gogsrp as a host group. 
- Variables are set in file roles/gogs/vars.

To run the playbook:

```
ansible-playbook -i inventory gogs_setup.yml
```
