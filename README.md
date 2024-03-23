Vector-role
=========

install test-role install vector


# Role Variables
--------------
Defaults = Укажите все Параметры которые вам нужно изменить:

### vector_version 
 Версия Вектора 
### vector_arch

Архитектура пакетов
### vector_path
Путь для установки
### vector_config_path
Путь для конфигурации
### vector_logs_path
Путь для логов программы 



Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: vector
      roles:
         - { role: vector-role }

License
-------

MIT

Author Information
------------------

Maxim Besedkin
