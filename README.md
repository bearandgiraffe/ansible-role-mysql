Role Name
=========

A role to install mysql.

Requirements
------------

None.

Role Variables
--------------

Available variables are listed below, along with default values:

```yml
mysql_db_name:      site
mysql_db_user:      vagrant
mysql_db_password:  vagrant
```

Dependencies
------------

None.

Example Playbook
----------------

```
- hosts: servers
  roles:
    - { role: bearandgiraffe.mysql, mysql_db_name: 'my_fancy_site' }
```

License
-------

The Unlicense (see LICENSE)

Author Information
------------------

Youssef Chaker (@ychaker) from Bear & Giraffe LLC (@bearandgiraffe).
