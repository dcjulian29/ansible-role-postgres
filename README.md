# Ansible Role: postgres

[![Lint](https://github.com/dcjulian29/ansible-role-postgres/actions/workflows/lint.yml/badge.svg)](https://github.com/dcjulian29/ansible-role-postgres/actions/workflows/lint.yml) [![GitHub Issues](https://img.shields.io/github/issues-raw/dcjulian29/ansible-role-postgres.svg)](https://github.com/dcjulian29/ansible-role-postgres/issues)

This an Ansible role to install a container running Postgres.

## Requirements

- Active Internet Connection.

## Installation

To use, use `requirements.yml` with the following git source:

```yaml
---
roles:
- name: dcjulian29.postgres
  src: https://github.com/dcjulian29/ansible-role-postgres.git
  ```

Then download it with `ansible-galaxy`:

```shell
ansible-galaxy install -r requirements.yml
```

## Dependencies

- None
