Role Name
=========
### hoplacloud.dump_mysql


Configure dump mysql with rotation for hopla.cloud linux system

Requirements
------------

Mysql root user with unix socket auth.

Role Variables
--------------

```
# Defaults file for hoplacloud.dump_mysql
dump_dir: "/var/mysql_backup"

# Default retention in days
retention: "3"
```

Dependencies
------------

None.

Example Playbook
----------------

    - hosts: localhost
      remote_user: root
      roles:
         - hoplacloud.dump_mysql

License
-------

GPLv3

Author Information
------------------

Joffrey Skandera for [hopla.cloud](https://hopla.cloud)
