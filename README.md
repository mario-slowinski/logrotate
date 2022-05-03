logrotate
=========

Ansible role to manage logrotate entries

Requirements
------------

* [ansible.builtin](https://docs.ansible.com/ansible/latest/collections/ansible/builtin/index.html)

Role Variables
--------------

* defaults

  * `main.yaml`

    ```yaml
    ```

Dependencies
------------

*No* *dependencies*

Tags
----

* **logrotate.config** - Update logrotat config

Examples
--------

* `requirements.yaml`

  ```yaml
  - name: logrotate
    src: https://github.com/mario-slowinski/logrotate
  ```

* `playbook.yaml`

  ```yaml
  - hosts: servers
    gather_facts: false

    roles:
      - role: logrotate
  ```

License
-------

[GPL-3.0](https://www.gnu.org/licenses/gpl-3.0.html)

Author Information
------------------

[mario.slowinski@gmail.com](mailto:mario.slowinski@gmail.com)
