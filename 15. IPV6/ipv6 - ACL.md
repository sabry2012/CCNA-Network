# ACL in IPV6
# Commands

In Router 0 :

Router(config)#ipv6 access-list NetworkGeek
Router(config-ipv6-acl)#deny ipv6 host 2001:1::2 host 2001:3::2
Router(config-ipv6-acl)#permit ipv6 any any
Router(config-ipv6-acl)#exit
Router(config)#do show access-list
IPv6 access list NetworkGeek
deny ipv6 host 2001:1::2 host 2001:3::2
permit ipv6 any any
Router(config)#int fa0/0
Router(config-if)#ipv6 traffic-filter NetworkGeek in
Router(config-if)#

