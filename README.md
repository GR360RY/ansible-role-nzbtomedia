Role Name
=========

A brief description of the role goes here.

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

HTPC-Ansible Project
--------------------

This role is part of HTPC-Ansible project that includes additional roles for building Ubuntu Based HTPC Server.

 Role name               | Comment
-------------------------|-----------------------------
[![Galaxy](http://img.shields.io/badge/galaxy-GR360RY.htpc--common-blue.svg?style=flat-square)](https://galaxy.ansible.com/GR360RY/htpc-common)   | Create htpc user and media folders
[![Galaxy](http://img.shields.io/badge/galaxy-GR360RY.htpc--nas-blue.svg?style=flat-square)](https://galaxy.ansible.com/GR360RY/htpc-nas)         | Configure NAS ( NFS, CIFS and AFP )
[![Galaxy](http://img.shields.io/badge/galaxy-GR360RY.kodi--client-blue.svg?style=flat-square)](https://galaxy.ansible.com/GR360RY/kodi-client)   | Install Kodi Media Player
[![Galaxy](http://img.shields.io/badge/galaxy-GR360RY.kodi--mysql-blue.svg?style=flat-square)](https://galaxy.ansible.com/GR360RY/kodi-mysql)     | Install MySQL Backend for Kodi
[![Galaxy](http://img.shields.io/badge/galaxy-GR360RY.deluge-blue.svg?style=flat-square)](https://galaxy.ansible.com/GR360RY/deluge)              | Install Deluge Bittornet Client
[![Galaxy](http://img.shields.io/badge/galaxy-GR360RY.nzbtomedia-blue.svg?style=flat-square)](https://galaxy.ansible.com/GR360RY/nzbtomedia)      | Install NZBtoMedia Postprocessing
[![Galaxy](http://img.shields.io/badge/galaxy-GR360RY.sickrage-blue.svg?style=flat-square)](https://galaxy.ansible.com/GR360RY/sickrage)          | Install SickRage
[![Galaxy](http://img.shields.io/badge/galaxy-GR360RY.couchpotato-blue.svg?style=flat-square)](https://galaxy.ansible.com/GR360RY/couchpotato)    | Install CouchPotato
[![Galaxy](http://img.shields.io/badge/galaxy-GR360RY.htpc--manager-blue.svg?style=flat-square)](https://galaxy.ansible.com/GR360RY/htpc-manager) | Install htpc-manager
<!-- 
[![Galaxy](http://img.shields.io/badge/galaxy-GR360RY.sabnzbd-blue.svg?style=flat-square)](https://galaxy.ansible.com/GR360RY/sabnzbd)            | Install Sabnzbd
[![Galaxy](http://img.shields.io/badge/galaxy-GR360RY.tvheadend-blue.svg?style=flat-square)](https://galaxy.ansible.com/GR360RY/tvheadend)        | Install Tvheadend

Additional Info is available at [www.htpc-ansible.org](http://www.htpc-ansible.org)
 -->
License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
