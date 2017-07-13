
Install Wordpress Blog
======================

In the directory 'ansible', there is a collection of very basic
ansible playbooks and other assorted material that installs
a wordpress blog on a machine.

**THIS IS NOT SUITABLE FOR PRODUCTION!**

Reason: No security is provided whatsoever. This is rather a
proof-of-concept thing.


As things stand, everything is installed together on one machine, and
it is just enough to get wordpress up and running.


This installation procedure has only been tested on Debian/stretch, so
if you are using something different, you are on your own.


This playbook installs some static content as well. If you want to
actually work with the wordpress, you need to first log in to the
machine and remove or rename this file: /var/www/html/index.html.

Also, the passwords are hardcoded, but you still have to create an
admin user by hand, via the web interface.


Enjoy!


LICENSE:

The entire thing is licensed under the AGPL (3 and up).
