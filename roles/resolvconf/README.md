resolvconf
=========

Настройка резолвера.

Requirements
------------

Статический IP. В случае использования DHCP, некоторые настройки из этой роли не будут применены.

Role Variables
--------------

- DNS_searchname - переменная должна содержать суффиксы поиска.
- DNS_IP - список серверов DNS.

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
