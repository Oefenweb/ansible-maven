## maven

[![CI](https://github.com/Oefenweb/ansible-maven/workflows/CI/badge.svg)](https://github.com/Oefenweb/ansible-maven/actions?query=workflow%3ACI)
[![Ansible Galaxy](http://img.shields.io/badge/ansible--galaxy-maven-blue.svg)](https://galaxy.ansible.com/Oefenweb/maven)

Set up [Apache Maven](https://maven.apache.org/).

#### Requirements

None

#### Variables

* `maven_version` [default: `3.6.3`]: Version to install
* `maven_install_prefix` [default: `/opt`]: Install prefix

## Dependencies

None

#### Example

```yaml
---
- hosts: all
  roles:
    - maven
```

#### License

MIT

#### Author Information

Mischa ter Smitten

#### Feedback, bug-reports, requests, ...

Are [welcome](https://github.com/Oefenweb/ansible-maven/issues)!
