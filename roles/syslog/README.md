syslog
=========

Настройка syslog для отправки событий на удалённый сервер. Выполняется при наличии значения переменной SYSLOG_IP.

Requirements
------------

Нет.

Role Variables
--------------

Переменные group vars:
- SYSLOG_IP

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
