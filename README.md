Role Name
=========

This role installs the Maestro Client in Java.

Build/Test Status
------------

Linux Build Status: [![Linux Build Status](https://api.travis-ci.org/msgqe/ansible-maestro-client.svg?branch=master)](https://travis-ci.org/msgqe/ansible-maestro-client)

Requirements
------------

The package libselinux-python is required for running the test.

Role Variables
--------------

| Name              | Default Value       | Description          |
|-------------------|---------------------|----------------------|
| `maestro_client_download_url` | null | Download URL |


Dependencies
------------


Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

  - hosts: localhost
    remote_user: root
    roles:
      - ansible-maestro-client

License
-------

Apache 2.0

Author Information
------------------

Messaging team @ redhat.com
