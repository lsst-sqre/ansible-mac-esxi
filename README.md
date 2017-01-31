ansible-mac-esxi
================

[![Build Status](https://travis-ci.org/jmatt/ansible-mac-esxi.svg?branch=master)](https://travis-ci.org/jmatt/ansible-mac-esxi)

Configure ESXI for LSST SQuaRE CI infrastructure.

* Configure the sshClient and sshServer services on ESXi.
* Configure `/etc/ssh/sshd_config`.
* Configure `/etc/ssh/keys-root/authorized`

Example Playbook
----------------

    - hosts: esxis
      roles:
         - { role: jmatt.mac-esxi }

License
-------

The MIT License. See the [LICENSE file](https://github.com/lsst-sqre/ansible-mac-esxi/blob/master/LICENSE).