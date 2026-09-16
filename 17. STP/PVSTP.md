# Per VLAN Spanning Tree Protocol (PVSTP)
# Commands

In Switch 0 :

Switch>en
Switch#conf t
Switch(config)#spanning-tree vlan 10 priority 4096
Switch(config)#

In Switch 1 :

Switch>en
Switch#conf t
Switch(config)#spanning-tree vlan 20 priority 4096
Switch(config)#

In Switch 2 :

Switch>en
Switch#conf t
Switch(config)#spanning-tree vlan 30 priority 4096
Switch(config)#
