proxy-settings
=========

Настройка системного прокси

Requirements
------------

Роль выполняется, если у переменной proxy_host есть значение.

Role Variables
--------------

Переменные из group vars:
- proxy_host
- proxy_port
- proxy_noproxy

Dependencies
------------

Нет.

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: proxy-settings }

License
-------

BSD

Author Information
------------------

Andrey
