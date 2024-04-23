zabbix-agent2
=========

Настройка агента для привязки к серверу Zabbix. Стартует, если определено значение переменной zabbix_IP.

Requirements
------------

Стартует, если определено значение переменной zabbix_IP.

Role Variables
--------------

Переменные group vars:
- zabbix_IP

Dependencies
------------

Нет.

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: zabbix-agent2 }

License
-------

BSD

Author Information
------------------

Andrey
