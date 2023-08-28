sudoers
=========

Настройка "mailto" в файле /etc/sudoers для отправки почтовых уведомлений. Стартует, если определено значение переменной admins_email.

Requirements
------------

Стартует, если определено значение переменной admins_email.

Role Variables
--------------

Переменные:
- admins_email

Dependencies
------------

Нет.

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: sudoers}

License
-------

BSD

Author Information
------------------

Andrey
