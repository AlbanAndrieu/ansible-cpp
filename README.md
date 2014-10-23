# ansible-cpp

A role for installing cpp.

[![Build Status](https://api.travis-ci.org/AlbanAndrieu/ansible-cpp.png?branch=master)](https://travis-ci.org/AlbanAndrieu/ansible-cpp)
[![Galaxy](http://img.shields.io/badge/galaxy-cpp-blue.svg?style=flat-square)](https://galaxy.ansible.com/list#/roles/0000)
[![Tag](http://img.shields.io/github/tag/AlbanAndrieu/ansible-cpp.svg?style=flat-square)]()

## Actions

- Ensures that cpp is installed (using `apt`)

Usage example
------------

    - name: Install cpp
      hosts: cpp
      remote_user: root
    
      roles:
        - cpp      

Requirements
------------

none

Dependencies
------------

none

License
-------

MIT

#### Feedback, bug-reports, requests, ...

Are [welcome](https://github.com/AlbanAndrieu/ansible-cpp/issues)!
