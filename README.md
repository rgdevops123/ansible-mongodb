# ansible-mongodb

- Install MongoDB Servers with Ansible.
- OS: CentOS 7

## Before Install
- Use DNS Server or update /etc/hosts for all servers.

### Install MongoDB Server.
- Run the playbook.

```
ansible-playbook -i hosts mongodb.yml
```
