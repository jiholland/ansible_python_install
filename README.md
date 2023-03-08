🐍 python\_install
==================

Build, compile and install Python from source code.

Requirements
------------

💿 [Community General](https://galaxy.ansible.com/community/general)

Role Variables
--------------

- python\_version
- python\_release\_version

Dependencies
------------

None.

Example Playbook
----------------

    ---
    - name: Build, compile and install Python from source code
      hosts: localhost
      gather_facts: true

      roles:
        - role: python_install
          tags: python

License
-------

BSD

Author Information
------------------

Jørn Ivar Holland
