influxdb
=================

Setup InfluxDB(work in progress)

OS Platform
-----------------

### Debian

- bookworm
- bullseye

Role Variables
--------------

設定方法の詳細については[defaults/main.yml](defaults/main.yml)のサンプルコードを参照してください。

### `influxdb_version`

Example Playbook
--------------

```yaml
- hosts: servers
  roles:
    - role: influxdb
```

License
--------------

Apache License 2.0
