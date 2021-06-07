# Ansible: Setup Docker

This playbook installs docker & docker-compose on your server.

## Installing 

Copy then change values of hosts example file

```bash
$ cp hosts.example.ini hosts.ini
```

Then run the playbook:

```bash
$ ansible-playbook -i hosts.ini playbook.yml
```
