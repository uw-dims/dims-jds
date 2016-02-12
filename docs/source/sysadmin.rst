.. _sysadmin:

=================================
System and Network Administration
=================================

The DIMS project primarily uses GNU/Linux operating systems. Integrating
multiple open source tools produced by others (with their choice of operating
system version, libraries, etc.) requires simultaneously dealing with multiple
Linux distributions and versions, where they place configuration files, how
they manage service daemons, etc. Using `Ansible`_ to control all of these
configuration files requires understanding how to identify and provide
installation steps for each supported operating system and use of
methodical development and testing practices to ensure that playbooks
run on all supported operating systems.

Automation of repetitive processes through the use of ``Makefile`` and/or
Bash scripts is used heavily in this project to facilitate build
automation.  Familiarity with BASH scripting and GNU/Linux command line tools
(e.g, ``awk``, ``sed``, ``grep``, ``make``) is a requirement.


Experience with the following operating systems:

+ CentOS 5.x & 6.x
+ RedHat Enterprise Linux 5.x, 6.x
+ Ubuntu 12.04 and 14.04 `LTS`_ releases
+ `CoreOS`_
+ Experience with bootable Linux ISO and USB distributions (e.g., `CAINE`_, Debian Mint)
+ Use of operating system installation automation tools like `Kickstart`_
  and `Preseed`_

Experience with the following system administration concepts and tasks:

+ Backup and restore
+ Build automation
+ Management of configuration files using a source code control system
  for version control, differencing between versions and across operating
  system distributions
+ Device naming and device management in multiple Linux distributions
+ Production, management, and revocation/replacement of encryption
  keys and certificates

Experience with the following network administration concepts and tasks:

+ TCP/IP networking (routing, VPN tunneling, VLANs, ``iptables`` firewalls)
+ Use of `OpenVPN`_ Virtual Private Network (VPN) and Virtual Local
  Area Network (VLAN) for network isolation
+ Fundamentals of routing protocols, static routing tables, subnet
  allocation and subnet masks, and use of `RFC 1918`_ non-routable
  address blocks as part of constructing a multi-layer `Private network`_
+ Using `iptables`_ for firewalling and `Network address translation`_ (NAT)
+ Designing networks for static and dynamic host provisioning (subnet
  allocation, device address allocation, VPN with static and dynamic
  address allocation, VLAN configuration on managed switches)
+ The Domain Name System (DNS), DNS recursion, "`Split Horizon DNS`_",
  and `dnsmasq`_
+ Understanding of Linux network interface card (NIC) device mapping,
  differences in device naming across multiple Linux operating system
  distributions, ability to identify and document the mapping of internal
  logical device names to physical NIC ports to properly cable systems in a
  multi-switch rack

Experience with the following operating system level tools:

+ `Ansible`_
+ `Vagrant`_
+ `Packer`_
+ Virtualization and hypervisors, including `Virtualbox`_
+ `Docker`_

Experience and/or ability to install, configure, and maintain the following
server software packages:

+ Unix ``syslog`` and ``rsyslog``
+ The `ELK stack`_
+ MySQL Ver 14.12 and above
+ PostgreSQL 8.4.17 and above
+ The `Collective Intelligence Framework`_ (CIF) v1.0 and above
+ SiLKTools v1.1.3
+ flowtools v0.68
+ HTML and CGI using `Apache`_ and `Nginx`_
+ `OpenVPN`_
+ `RabbitMQ`_
+ `Botnets`_ v0.95 (customized)

Experience with rack-mounted hardware:

+ Planning rack layout
+ Planning network cabling between layered switches/VLANs and to
  NICs in servers and orderly cable management

.. _LTS: https://wiki.ubuntu.com/LTS
.. _CoreOS: https://coreos.com
.. _Kickstart: https://en.wikipedia.org/wiki/Kickstart_%28Linux%29
.. _Preseed: https://en.wikipedia.org/wiki/Preseed
.. _dnsmasq: http://en.wikipedia.org/wiki/Dnsmasq
.. _Split Horizon DNS: http://homepage.ntlworld.com./jonathan.deboynepollard/FGA/dns-split-horizon.html
.. _CAINE: http://www.caine-live.net/
.. _Ansible: http://www.ansible.com/get-started
.. _Vagrant: https://www.vagrantup.com/
.. _Packer: https://www.packer.io/
.. _Virtualbox: https://www.virtualbox.org/
.. _Docker: https://www.docker.com/
.. _Collective Intelligence Framework: http://code.google.com/p/collective-intelligence-framework/
.. _ELK stack: http://www.elasticsearch.org/overview/
.. _OpenVPN: https://openvpn.net/
.. _iptables: https://wiki.centos.org/HowTos/Network/IPTables
.. _RFC 1918: https://tools.ietf.org/html/rfc1918
.. _Private network: https://en.wikipedia.org/wiki/Private_network
.. _Network address translation: https://en.wikipedia.org/wiki/Network_address_translation
.. _Apache: http://httpd.apache.org/
.. _Nginx: http://wiki.nginx.org/Main
.. _RabbitMQ: http://www.rabbitmq.com/
.. _Botnets: http://botnets.org/
