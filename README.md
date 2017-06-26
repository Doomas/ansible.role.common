Common
======

Common role for all my hosts



Role Variables
--------------

interfaces_ipv4:   # A list of ipv4 interfaces to configure
  - name:             # Name of the Interface ( eth0)
    mode:             # Mode (static, dhcp, manual) 
    address:          # IP Adrress of the Intercface
    netmask:          # Netmask fot the interafce
    gateway:          # Gateway for the interface
