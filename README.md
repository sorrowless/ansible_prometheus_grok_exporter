# sbog/prometheus_grok_exporter

[![Build Status](https://travis-ci.com/sorrowless/ansible_prometheus_grok_exporter.svg?branch=master)](https://travis-ci.com/sorrowless/ansible_prometheus_grok_exporter)
[![Ansible Role](https://img.shields.io/ansible/role/54624)](https://galaxy.ansible.com/sorrowless/prometheus_grok_exporter)
[![Ansible Quality Score](https://img.shields.io/ansible/quality/54624)](https://galaxy.ansible.com/sorrowless/prometheus_grok_exporter)
[![Ansible Role](https://img.shields.io/ansible/role/d/54624)](https://galaxy.ansible.com/sorrowless/prometheus_grok_exporter)
[![GitHub](https://img.shields.io/github/license/sorrowless/ansible_prometheus_grok_exporter)](https://github.com/sorrowless/ansible_prometheus_grok_exporter/blob/master/LICENSE)

An Ansible role which installs and configures [Prometheus grok_exporter](https://github.com/fstab/grok_exporter) on Linux

## Requirements

Ansible 2.8+

## Role Variables

You can see all vars in `defaults/main.yml` vars file.

## Dependencies

None

## Example Playbook

```yaml
- name: Ensure prometheus_grok_exporter
  hosts: prometheus_grok_exporters
  remote_user: root

  roles:
    - prometheus_grok_exporter
```

## License

Apache 2.0

## Author Information

This role was created by [Stan Bogatkin](https://sbog.ru).
