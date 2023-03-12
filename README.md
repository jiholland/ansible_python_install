🐍 python\_install
==================

Build, compile and install Python from source code.

Requirements
------------

💿 [Community General](https://galaxy.ansible.com/community/general)

Role Variables
--------------

- python\_release\_version
- python\_install\_dir
- python\_url
- python\_jobs
- python\_state

Dependencies
------------

None.

Example Playbook
----------------

    ---
    - name: Download, build, compile and install Python from source code.
      hosts: localhost
      gather_facts: true

      roles:
        - python

License
-------

BSD

Author Information
------------------

Jørn Ivar Holland
