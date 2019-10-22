User Management
=========

Allow to create an user with a group and add that group to sudousers.

Requirements
------------

Python 3 installed

Role Variables
--------------

```yml
user: {{ YOUR_USERNAME }}
group: {{ YOUR_GROUP }}
shell: /bin/bash
```

Example Playbook
----------------

```yml
  - hosts: servers
    roles:
      - name: duffmck.user
        vars:
          - user: franco
          - group: francos
```

License
-------

MIT
