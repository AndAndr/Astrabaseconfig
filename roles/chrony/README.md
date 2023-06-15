chrony
=========

Настройка chrony: удаление дефолтных серверов, добавление внутренних серверов времени.

Requirements
------------

Нет.

Role Variables
--------------

Переменные group vars:
- NTP_IP1 
- NTP_IP2 значение переменной может отсутствовать
- NTP_IP3 значение переменной может отсутствовать

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
