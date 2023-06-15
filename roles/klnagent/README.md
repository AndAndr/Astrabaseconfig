klnagent
=========

"Тихая" установка агента Касперского, привязка его к KSC. Стартует, если определено значение переменной KSC_server.

Requirements
------------

1. Стартует, если определено значение переменной KSC_server.
2. Необходимо поместить дистрибутив (пакет .deb) агента в /roles/klnagent/files/tmp/klnagent/ (например:klnagent64_14.2.0-23324_amd64.deb)

Role Variables
--------------

Переменные group vars:
- KSC_server

Dependencies
------------

Нет.

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: klnagent}

License
-------

BSD

Author Information
------------------

Andrey
