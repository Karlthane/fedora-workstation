Fedora-Workstation
=========

This role configures a fedora workstation install to have the packages and configuration files I prefer.
It installs a set of packages both rpm and flatpak. It modifies .bash_profile, .tmux.conf, and .vimrc for powerline. It adds config file to polkit to enable sudo access through accounts accessed via freeipa. It uses dconf to enable and configure gnome nightlight. This role also configures fedora to use a yubikey for u2f and gpg.

Requirements
------------

Any pre-requisites that may not be covered by Ansible itself or the role should be mentioned here. For instance, if the role uses the EC2 module, it may be a good idea to mention in this section that the boto package is required.

Role Variables
--------------

A description of the settable variables for this role should go here, including any variables that are in defaults/main.yml, vars/main.yml, and any variables that can/should be set via parameters to the role. Any variables that are read from other roles and/or the global scope (ie. hostvars, group vars, etc.) should be mentioned here as well.

Dependencies
------------

A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: username.rolename, x: 42 }

License
-------

MIT

Author Information
------------------

Alex Thomas
@karlthane on twitter,discord,irc,github
karlthane@(gmail.com,live.com)
