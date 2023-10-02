syslog-ng
=========

Настройка syslog-ng для отправки событий на удалённый сервер. Выполняется при наличии значения переменной SYSLOG_IP.

Requirements
------------

Нет.

Role Variables
--------------

Переменные group vars:
- SYSLOG_IP
- SYSLOG_PORT
- SYSLOG_PROTO

Dependencies
------------

Нет.

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: syslog }

License
-------

BSD

Author Information
------------------

Andrey
