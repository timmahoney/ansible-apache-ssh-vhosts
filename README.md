Apache
========

Apache Web Server

Requirements
------------

None

Role Variables
--------------

Config file is completely parameterized. You can find both a full default mapping of the httpd.conf, welcome.conf, and ssl.conf files in the main.yml file, so that from there you can generate your own mappings.



Dependencies
------------

None

Example Playbook
-------------------------

    - hosts: servers
      roles:
         - apache

License
-------

BSD

Author Information
------------------

Timothy Mahoney
timothymahoney.com
twitter.com/timothymahoney
