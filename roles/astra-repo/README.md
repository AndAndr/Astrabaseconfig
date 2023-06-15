astra-repo
=========

Добавление локального репозитория Astra Linux.

Requirements
------------

No

Role Variables
--------------

Используются (group vars) переменные AstraSE_localrepo, AstraSE_localrepo в зависимости от значения ansible_os_family.

Dependencies
------------

No

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: astra-repo }

License
-------

BSD

Author Information
------------------

Andrey
