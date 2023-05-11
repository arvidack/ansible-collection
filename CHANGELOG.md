# v1.0.5

## Feature

- Added userparameter reload to Zabbix agent role. It will trigger if `param_userparamater` was changed and no agent restart detected.
- Added logrotate customization and extended new defaults with maxsize option.
- Added support of self-managed certificates for Zabbix agent connections.
- Added support of self-managed certificates for Zabbix agent2 plugin sessions.
- Added `remove` tag to uninstall agent packages.
  ```bash
  ansible-playbook -i inventory play.yml -t remove
  ```
- Added `userparam` tag to manage user parameters only.
  ```bash
  ansible-playbook -i inventory play.yml -t userparam
  ```

# v1.0.4

## Feature

- Zabbix agent role extended distribution support for:
    - CentOS Stream 8,9

# v1.0.3

## Feature

- Zabbix agent role extended distribution support for:
    - Alma Linux 8,9 
    - Rocky Linux 8,9
    - Oracle Linux 8,9

# v1.0.2

## Bug fix

- Zabbix agent parameter fixes.
