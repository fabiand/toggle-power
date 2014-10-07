
toggle-power
============

A simple script to toggle the power of machines on the local lan using
suspend to RAM and wake-on-lan


Assumptions
-----------

* Local
  - wol is installed
  - mdns based name resolution is enabled
  - password-less ssh into remote machine
* Remote
  - Can be woken up using wol
  - Can be suspended using systemctl suspend
  - Publishes it#s name using mdns


Usage
-----

    $ toggle-power <hostname>
