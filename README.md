Vector
=========

This role can install vector

vector_version: "0.21.1"
vector_os_arh: "x86_64"
vector_workdir: "/tmp/vector"
vector_os_user: "vector"
vector_os_group: "vector"
vector_data_dir: "/var/lib/vector"

Role Variables
--------------
|vars|description|
|--|--|
|vector_version| версия vector |
|--|--|
|vector_os_arh| для какой архитектуры дистрибутива |
|--|--|
|vector_workdir| рабочая папка |
|--|--|
|vector_os_user| имя пользователя |
|--|--|
|vector_os_group| группа |
|--|--|
|vector_data_dir| data folder |
|--|--|

Dependencies
------------

A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles.

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: vector }

License
-------

MIT

Author Information
------------------

Andrey Chikin
