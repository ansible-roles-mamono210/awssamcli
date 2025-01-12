[![CircleCI](https://circleci.com/gh/ansible-roles-mamono210/awssamcli/tree/main.svg?style=svg)](https://circleci.com/gh/ansible-roles-mamono210/awssamcli/tree/main)

Role Description
=========

Installs [AWS SAM CLI](https://github.com/aws/aws-sam-cli) for CentOS Stream 9.

Requirements
------------

None

Role Variables
--------------

```YAML
awssamcli_working_dir: /tmp/awssamcli_working_dir
```

Dependencies
------------

None

Example Playbook
----------------

```YAML
---
- hosts: all
  become: true
  roles:
    - awssamcli
```

License
-------

BSD
