## Описание репозитория
- ***roles/*** - Расположены роли 
- ***playbooks/*** - Расположены плейбуки с реализацией небольших задач
- ***ConfigureRemotingForAnsible.ps1*** - PowerShell скрипт для включения winrm на Windows хостах для подключения ansible

[README playbooks](playbooks/README.md)
## Описание ролей
### docker
Устанавилвает docker в систему, работает на RedHat-based, Debian-based, Astra Linux

Подробнее - [README](roles/docker/README.md)
### gitlab-runner
Устанавливает на хост gitlab runner, и подключает его к gitlab серверу (Поддерживает self-hosted инстансы и gitlab.com).

Подробнее - [README](roles/gitlab-runner/README.md)
### zabbix-agent
Устанавливает на хост zabbix agent и подключает его к серверу Zabbix с базовой конфигурацией. Поодерживает RedHat-based, Debian-based, Astra Linux. Реализована установка обоих версий агента.

Подробнее - [README](roles/zabbix-agent/README.md)

### proxy_server
Устанавливает на хост squid прокси и лог аналайзер сетевой активности. Поддерживает Debian-based дистрибутивы.

Подробнее - [README](roles/proxy_server/README.md)