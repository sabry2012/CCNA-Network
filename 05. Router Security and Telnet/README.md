# Router Security and Telnet

## Router Security
# Commands

In Router 0 :
Router(config)#enable secret cisco123
Router(config)#
Router(config)#do show running-config
Building configuration...
Current configuration : 535 bytes
!
version 12.4
no service timestamps log datetime msec
no service timestamps debug datetime msec
service password-encryption
!
hostname Router
!
!
enable secret 5 $1$mERr$5.a6P4JqbNiMX01usIfka/
!



