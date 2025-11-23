# Role Name
------------

Роль для установки lighthouse.

- устновка Git

- скачивание lighthouse из репозитория

- конфигурирование lighthouse

# Requirements
------------

- установка git

- установка и настройка Nginx

# Role Variables
--------------

    clickhouse_user: user
    clickhouse_password: 1234

Переменные для скачивания Lighthouse из Git:

    lighthouse_vcs: https://github.com/VKCOM/lighthouse.git
    lighthouse_dir: /var/lib/lighthouse
    lighthouse_access_log_name: lighthouse_access

# Dependencies
------------

# Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    hosts: lighthouse
    roles:
      - role: lighthouse-role

# License
-------

MIT

# Author Information
------------------

Ivan Shkutov
