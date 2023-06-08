Ansible Role: VS Code
=====================

An Ansible Role that installs [Microsoft Visual Studio Code][1].

Requirements
------------

None.

Role Variables
--------------

Available variables are listed below, along with default values (see defaults/main.yml).

You can control the build to be installed:

    vscode_build: stable

The `vscode_build` should be either `stable` or `insiders`.

Dependencies
------------

None.

Example Playbook
----------------

    - hosts: servers
      roles:
        - { role: ihmels.vscode }

License
-------

MIT

[1]: https://code.visualstudio.com
