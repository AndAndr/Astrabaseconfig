resolvconf
=========

Настройка резолвера.

Requirements
------------

Статический IP. В случае использования DHCP, некоторые настройки из этой роли не будут применены.

Role Variables
--------------

DNS_searchname - переменная должна содержать суффиксы поиска.
- DNS_IP1 - 1-й DNS
- DNS_IP2 - 2-й DNS если нет, можно не указывать
- DNS_IP3 - 3-й DNS если нет,можно не указывать

Dependencies
------------

Нет.

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: resolvconf }

License
-------

BSD

Author Information
------------------

Andrey
