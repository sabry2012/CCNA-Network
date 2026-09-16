# FIRST HOP REDUNDANCY PROTOCOL (FHRP)
# HSRP
# Commands

In Router 1 :

Router>en
Router#conf t
Enter configuration commands, one per line. End with CNTL/Z.
Router(config)#int fa0/0
Router(config-if)#standby 1 ip 192.168.1.1
Router(config-if)#

In Router 2 :

Router>en
Router#conf t
Enter configuration commands, one per line. End with CNTL/Z.
Router(config)#int fa0/0
Router(config-if)#standby 1 ip 192.168.1.1
Router(config-if)#

