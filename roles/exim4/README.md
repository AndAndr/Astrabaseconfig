exim4
=========

Настройка exim4 для возможности отправки почтовых уведомлений. Стартует, если определено значение переменной exim_smarthost.

Requirements
------------

Стартует, если определено значение переменной exim_smarthost.

Role Variables
--------------

Переменные:
- admins_email
- exim_smarthost

Dependencies
------------

Нет.

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: exim4}

License
-------

BSD

Author Information
------------------

Andrey
