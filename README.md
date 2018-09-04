Ansible JBoss Fuse Role [![Build Status](https://travis-ci.org/redhat-cop/jboss_fuse.svg)](https://travis-ci.org/redhat-cop/jboss_fuse)
=================

A role to install JBoss Fuse ESB on RHEL7. Intended to be used with [JBoss Middleware Playbooks](https://github.com/redhat-cop/ansible-middleware-playbooks)

Transfer Method
------------

This role supports a few different mechanism for transferring the product zip files to the target host. These are documented on [the main playbooks README](https://github.com/redhat-cop/ansible-middleware-playbooks), as the methods are supported across a variety of roles.


Dependencies
------------

- java
- unzip

Our playbooks provide these dependencies in a [common role](https://github.com/redhat-cop/ansible-middleware-playbooks/tree/master/roles/common), but this there is no explicitly ansible dependency to allow end users more options.

Example Playbooks
----------------

- [JBoss Fuse 6.2.1 on CentOS 7](https://github.com/redhat-cop/ansible-middleware-playbooks/blob/master/fuse6.2-centos7-csp.yml)
- [JBoss Fuse 6.2.1 on RHEL 7](https://github.com/redhat-cop/ansible-middleware-playbooks/blob/master/fuse6.2-rhel7.yml)

License
-------

[LICENSE](./LICENSE)

Authors Information
------------------

* [Andrew Block](https://github.com/sabre1041)
* [Albert Wong](https://github.com/alberttwong)
* [Justin Holmes](https://github.com/sherl0cks)
* [Kamesh Sampath](https://github.com/kameshsampath)
