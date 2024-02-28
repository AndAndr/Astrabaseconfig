ca-certs
=========

Установка CA сертификатов.

Requirements
------------

Поместить файлы сертификатов в /roles/ca-certs/files/usr/local/share/ca-certificates/

Role Variables
--------------

No

Dependencies
------------

No

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: ca-certs }

License
-------

BSD

Author Information
------------------

Andrey
