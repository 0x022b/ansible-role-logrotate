# Ansible Role: logrotate

![Ansible Galaxy](https://github.com/0x022b/ansible-role-logrotate/workflows/Ansible%20Galaxy/badge.svg)

Ansible role that configures logrotate package.

## Requirements

None.

## Role Variables

Available variables are listed below with default values.

```yaml
logrotate_package_state: present
```

Variable to control the state of logrotate package.

## Dependencies

None.

## Example Playbook

```yaml
- hosts: servers
  roles:
    - role: 0x022b.logrotate
```

## Versioning

This project uses [Semantic Versioning][semver].

## License

MIT

[semver]: https://semver.org/
