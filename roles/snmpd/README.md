snmpd
=========

Настройка snmpd.

Requirements
------------

Нет.

Role Variables
--------------

Переменные group vars:
- SNMP_sysLocation
- SNMP_sysContact
- SNMP_IP1
- SNMP_IP2
- SNMP_IP3
- SNMP_IP4
- SNMP_ROcommunity1
- SNMP_ROcommunity2

Dependencies
------------

Нет.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: snmpd }

License
-------

BSD

Author Information
------------------

Andrey
