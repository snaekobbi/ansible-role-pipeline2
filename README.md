# ansible-role-pipeline2

Ansible role for installing DAISY Pipeline 2

To import this role, create a file `install_roles.yml`:

```yml
- src: https://github.com/snaekobbi/ansible-role-pipeline2
  name: pipeline2
```

and run the following command:

```sh
ansible-galaxy install -r install_roles.yml -p roles
```
