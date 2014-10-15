# ansible-cpp

A role for installing cpp.

[![Build Status](https://api.travis-ci.org/AlbanAndrieu/ansible-cpp.png?branch=master)](https://travis-ci.org/AlbanAndrieu/ansible-cpp)

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
