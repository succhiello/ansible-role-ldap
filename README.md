# LDAP Modules for Ansible

This project contains a pair of [Ansible](http://www.ansible.com/home) modules
for manipulating an LDAP directory. `ldap_entry` can be used to ensure that an
entire entry exists and `ldap_attr` can be used to ensure the values of an
entry's attributes.

Regrettably, Ansible does not have any sensible mechanism for packaging and
distributing third-party modules with rendered documentation and runnable unit
tests. The LDAP modules do have complete documentation strings embedded.

I find these modules useful for one of my deployments and I welcome anyone else
to use or distribute them under the BSD license.
