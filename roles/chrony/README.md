chrony
=========

Настройка chrony: удаление дефолтных серверов, добавление внутренних серверов времени.

Requirements
------------

Нет.

Role Variables
--------------

Переменные group vars:
- NTP_IP

Dependencies
------------

Нет.

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: chrony }

License
-------

BSD

Author Information
------------------

Andrey
