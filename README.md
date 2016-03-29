# ansible-ubuntu-docker-repository-ldap
Ansible role to setup simple docker repository with htpasswd users list created from ansible variable.

## Define users

Users must be defined in ansible variable:

```
docker_registry_users:
  user1: password1
  user2: password2
```

