network-mdns
========

An [ansible role](https://galaxy.ansibleworks.com/list#/roles/212) to enable
[mdns](https://en.wikipedia.org/wiki/Zero_configuration_networking) (aka:
zeroconf, bonjour, avahi) link-local hostname look-up and service discovery.

Requirements
------------

An installation of [Fedora](https://fedoraproject.org/get-fedora).

Role Variables
--------------

The [firewalld](https://docs.fedoraproject.org/en-US/Fedora/19/html/Security_Guide/sect-Security_Guide-Using_Firewalls.html#sec-Introduction_to_firewalld)
zones in which to open the mdns port (default: all zones):

    network_mdns_zones:
      - home
      - internal
      - public
      - work
      - external

Dependencies
------------

None.

License
-------

BSD
