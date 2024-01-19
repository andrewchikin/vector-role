Vector
=========

This role can install vector:

установка Vector из архива
первичная конфигурация Vector с конфигурацией по генерации событий syslog и отправка данных в Clickhouse
создание пользователя ОС для Vector

Role Variables
--------------
|vars|description|
|vector_version| версия vector |
|vector_os_arh| для какой архитектуры дистрибутив |
|vector_workdir| рабочая папка |
|vector_os_user| имя пользователя |
|vector_os_group| группа |
|vector_data_dir| data folder |


Dependencies
------------

A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles.

Example Playbook
----------------
```yaml
- name: Install Vector
  hosts: vector
  gather_facts: false
  roles:
    - role: vector-role
      tags: vector
``` 

License
-------

MIT

Author Information
------------------

Andrey Chikin
