Ansible Docker [![Build Status](https://travis-ci.org/FinalDes/ansible-docker-ce.svg?branch=master)](https://travis-ci.org/FinalDes/ansible-docker-ce)
=========

A brief description of the role goes here.

Requirements
------------

Look official OS support before setup. Not every version of Ubuntu have all type of branch.

Role Variables
--------------
**branch**: docker distrubution branch (stable/test/edge/nightly), **default:** stable
**compose**: set true when need docker compose into machine, **default:** false
**compose_version**: docker compose version want to download **default:**  1.25.5

Dependencies
------------

A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles.

Example Playbook
----------------

Setup docker-ce stable branch. Incorrect branch will fail the task.

``` YAML
  - hosts: servers
    roles:
       - { role: docker-ce, branch: stable }
```

License
-------

MIT

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
