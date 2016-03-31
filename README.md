awscli
======

Installs awscli, and creates a credentials file so that commands work

Requirements
------------

This role requires Ansible 1.4 or higher.

Role Variables
--------------

| Name                  | Default | Description                                     |
|-----------------------|---------|-------------------------------------------------|
| awscli_version        | 1.10.4  | Default installed version of awscli             |
| awscli_user 	        | ubuntu  | Default user for credentials to be stored under |
| aws_access_key_id     | none    | AWS key to use                                  |
| aws_secret_access_key | none    | AWS secret to use                               |


Dependencies
------------

- kbrebanov.pip

Example Playbook
----------------

Install awscli
```
- hosts: all
  roles:
    - ctoaas.awscli
```

License
-------

BSD

Author Information
------------------

Kevin Brebanov
Craig Edmundss
