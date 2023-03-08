🐍 python\_install
==================

Build, compile and install Python from source code.

Requirements
------------

💿 [Community General](https://galaxy.ansible.com/community/general)

Role Variables
--------------

- python\_version

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
        - python_install

License
-------

BSD

Author Information
------------------

Jørn Ivar Holland
