Ansible role Lighthouse
=========

This role installs Lighhouse to host with CentOS 7

Requirements
------------


Role Variables
--------------
Git repository
```
    lighthouse_url: "https://github.com/VKCOM/lighthouse.git"
```
Directory 
```
    lighthouse_dir: "/home/maksim/lighthouse"
```
Dependencies
------------

You must install `Git` and `Nginx` to the correct work of the `Lighnhouse`.

Example Playbook
----------------

```yml
- name: Install Lighthouse
  hosts: lighthouse
  roles:
    - lighthouse-role
```


License
-------

MIT

Author Information
------------------
