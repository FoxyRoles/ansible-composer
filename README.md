# ansible-composer

Setups composer PHP packaging system.

### Example playbook
```yaml
---
- hosts: myserver
  roles:
    - role: sunfoxcz.composer
      composer_install_path: /usr/local/bin/composer      # optional
      composer_update_cron_path: /etc/cron.daily/composer # optional
```

## License

Licensed under MIT license. See [LICENSE](LICENSE.md) for details.
