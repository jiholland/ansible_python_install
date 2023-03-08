🐍 ansible\_python
==================

Install Python from source.

Requirements
------------

[Community General](https://galaxy.ansible.com/community/general)

Role Variables
--------------

- python\_version
- python\_\release\_version

Dependencies
------------

None.

Example Playbook
----------------

    ---
    - name: Install Python from source
      hosts: localhost
      gather_facts: true

      roles:
        - role: ansible_python
          tags: python


License
-------

BSD

Author Information
------------------

Jørn Ivar Holland
