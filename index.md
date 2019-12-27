
## Default Variables

### mas_email

Email to login to Appstore

#### Default value

```yaml
mas_email:
```

### mas_install_apps

List of apps to install

#### Default value

```yaml
mas_install_apps: []
```

#### Example usage

```yaml
mas_install_apps:
  - app1
  - id: 12345
    name: app2
```

### mas_password

Password to login to Appstore

#### Default value

```yaml
mas_password:
```

### mas_remove_apps

List of apps to remove

#### Default value

```yaml
mas_remove_apps: []
```

#### Example usage

```yaml
mas_remove_apps:
  - app1
  - id: 12345
    name: app2
```

### mas_upgrade

Perform an upgrade for all apps

#### Default value

```yaml
mas_upgrade: false
```

### mas_user

User to run user-specific commands

#### Default value

```yaml
mas_user | default(homebrew_user) | default(ansible_user_id)
```
## Dependencies

None

## License

Apache-2.0

## Author

Thomas Boerger
