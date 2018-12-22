# Ansible Role: settings

[![Build Status](https://img.shields.io/travis-ci/sbaerlocher/ansible.settings.svg?branch=master&style=popout-square)](https://travis-ci.org/sbaerlocher/ansible.settings) [![license](https://img.shields.io/github/license/mashape/apistatus.svg?style=popout-square)](https://sbaerlo.ch/licence) [![Ansible Galaxy](http://img.shields.io/badge/ansible--galaxy-settings-blue.svg?style=popout-square)](https://galaxy.ansible.com/sbaerlocher/settings) [![Ansible Role](https://img.shields.io/ansible/role/d/id.svg?style=popout-square)](https://galaxy.ansible.com/sbaerlocher/settings)

## Description

This is a role that makes different system settings under windows.

## Installation

```bash
ansible-galaxy install sbaerlocher.settings
```

## Requirements

None

## Role Variables

See Tasks

## Dependencies

None

## Example Playbook

```yml
- hosts: all
  roles:
     - sbaerlocher.settings
```

## Changelog

### 1.0.0

* inital commit

## Author

* [Simon Bärlocher](https://sbaerlocher.ch)

## License

This project is under the MIT License. See the [LICENSE](https://sbaerlo.ch/licence) file for the full license text.

## Copyright

(c) 2019, Simon Bärlocher
