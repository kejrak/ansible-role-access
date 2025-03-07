# Ansible role: access

### Description

Ansible role to handle user's access to remote hosts.

### Variables

All variables which can be overridden are stored in *defaults/main.yaml* file as well as in table below.

| Name           | Default Value | Description                                                        |
| -------------- | ------------- | ------------------------------------------------------------------ |
| `access_users` | []            | Name of the user and theirs public key. (**name**, **public_key**) |

### Overrides

You can **override** the default value of **access_users** in inventory file stored in *groups_vars/all.yaml*.

```
user-access_users: []
  # - name: "thomasbrody"
  #   public_key: "ssh-rsa AAAAB3NzaC1yc2EAAAADAQABAAABgQDNUm1Ww8NaAsWRM..."
```