pkgs-mgmt
=========

Удаление и установка пакетов, в соответствии со значениями переменных pkg2remove и pkg2install.
Остановка ntp для корректного старта chrony; установка open-vm-tools, если хост - это ВМ; установка zabbix-agent, если переменная zabbix_IP имеет значение.

Requirements
------------

Требуется доступ к репозиториям.

Role Variables
--------------

Переменные group vars:
- pkg2remove
- pkg2install
- zabbix_IP

Dependencies
------------

Запускать после роли resolvconf, astra-repo.

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: pkgs-mgmt }

License
-------

BSD

Author Information
------------------

Andrey
