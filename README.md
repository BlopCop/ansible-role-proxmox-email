Role Name
=========

This role sets up email alerts for proxmox server following this [guide](https://technotim.live/posts/proxmox-alerts/).

Requirements
------------

Root email should be set on the proxmox hosts. 

Role Variables
--------------

* 'proxmox_email_smtp_server': Address of the smtp server.
* 'proxmox_email_smtp_port': The port to use on the smtp server.
* 'proxmox_email_address': Email address to be used to send alert emails.
* 'proxmox_email_username': The username the emails will be sent from (default: ansible_nodename).


Dependencies
------------

A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: pvehosts
      roles:
         - { role: username.rolename, x: 42 }

License
-------


Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
