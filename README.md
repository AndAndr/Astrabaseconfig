# Astrabaseconfig
Ansible playbook baseconfig for AstraLinux SE

## 12 ролей:
1. Настройка резолвера - **resolvconf**
2. Настройка системного прокси - **proxy-settings**
3. Настройка локального репозитория - **astra-repo**
4. Удаление и добавление пакетов - **pkgs-mgmt**
5. Настройка syslog-ng для отправки событий на удалённый сервер - **syslog-ng**
6. Установка и настройка snmpd для работы систем мониторинга - **snmpd**
7. Настройка синхронизации времени с пом. chrony - **chrony**
8. Настройка exim для возможности отправки почты - **exim4**
9. Установка и настройка агента Zabbix - **zabbix-agent**
10. Установка и настройка агента Касперского - **klnagent**
11. Настройка sudoers для отправки почтовых сообщений - **sudoers**
12. Настройка sshd для показа баннера - **sshd**


роли **resolvconf, astra-repo, pkgs-mgmt** должны выполняться до выполнения остальных ролей

## Перед использованием нужно:
- скорректировать файл group_vars/all.yaml, настроив его переменные под свои нужды
- добавить дистрибутив .deb агента Касперского в каталог roles/klnagent/files/tmp/klnagent/

## usage:
- `ansible-playbook astrabaseconfig.yml`
- для выполнения только некоторых ролей можно использовать тэги, например так:

`ansible-playbook astrabaseconfig.yml --tags "resolvconf,astra-repo,pkgs-mgmt,exim4"`


