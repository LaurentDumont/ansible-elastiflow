Ansible Elasticflow role.
=========

Launch containers for Elastiflow instead of using docker-compose.

Reference : https://github.com/robcowart/elastiflow

Role Variables
--------------

ES_DATA_DIR : Folder for ES data and indexses.
ES_GIT_DIR: Folder for Git clone of repository.



```yaml
ES_DATA_DIR: /var/lib/elastiflow_es
ES_GIT_DIR: /srv/elastiflow-git
```

Example Playbook
----------------

This is an example of how to use this role:

```yaml
---
- hosts: docker-hosts
  become: yes
  roles:
    - ansible-elastiflow

```

License
-------

MIT
