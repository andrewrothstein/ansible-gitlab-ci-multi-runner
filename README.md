spk83.gitlab-runner
======================================
[![Build Status](https://travis-ci.org/spk83/ansible-gitlab-runner.svg?branch=master)](https://travis-ci.org/spk83/ansible-gitlab-runner)

Installs and configures a [GitLab Runner](https://gitlab.com/gitlab-org/gitlab-runner).

Requirements
------------

See [meta/main.yml](meta/main.yml)

Role Variables
--------------

See [defaults/main.yml](defaults/main.yml)

Dependencies
------------

See [meta/main.yml](meta/main.yml)

Example Playbook
----------------

```yml
- hosts: servers
  roles:
    - spk83.gitlab-runner
```

License
-------

MIT

Author Information
------------------

Andrew Rothstein <andrew.rothstein@gmail.com>

Contributors
------------

Vishal Shah <vishal.shah@nyu.edu>
