https://travis-ci.org/KyleNesium/ansible-role-prometheus.svg?branch=master

# Ansible Role for Prometheus

This ansible role will install Prometheus and Alertmanager.

## Requirements

_None._

## Role Variables

```
prometheus_version: 1.7.1
prometheus_host_domain_name: localhost
```

```
alertmanager_version:0.8.0
```

## Dependencies

_None._

## Example Playbook

```
- hosts: servers
  roles:
    - { role: kylenesium.prometheus }
```

## License

MIT

## Author Information

Kyle Steenkamp
