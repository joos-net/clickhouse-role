Role Name
=========

This role can install clickhouse and create db with table

Requirements
------------

Ansible >= 2.7 (It might work on previous versions, but we cannot guarantee it)

Role Variables
--------------

|vars|description|
|----|-----------|
|clickhouse_version|Version of Clickhouse to install|
|clickhouse_packages|List of packages to install|
|db_name|Clickhouse DB name|
|table_name|Clickhouse table name|

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: clickhouse-role }


Author Information
------------------

Ewgenij Ostrowskij