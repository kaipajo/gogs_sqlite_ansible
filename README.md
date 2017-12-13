# Gogs ansible installation

Gogs installation using sqlite. Nginx in front of Gogs. 

- Inventory file contains all host related information. Currently using gogsrp as a host group. 
- Variables are set in file roles/gogs/vars 

To run the playbook:

```
ansible-playbook -i inventory gogs_setup.yml
```

Remember to use --ask-pass and --ask-sudo if not using ssh keys or passwordless sudo. 


## Sqlite backups

See *https://sqlite.org/backup.html*
