# Configuring a Router

## Objective

Configure basic settings on a Cisco router and switch, assign IP addresses, and verify network connectivity between devices.

## Skills Practiced

- Router Initial Configuration
- Switch Management Configuration
- IP Address Assignment
- Interface Configuration
- Password Security
- Remote Access Configuration
- Connectivity Verification

## Key Commands

```cisco
hostname R1
hostname S1
no ip domain-lookup
enable secret class
service password-encryption
line console 0
line vty 0 4
interface g0/0/0
ip address 192.168.1.1 255.255.255.0
no shutdown
banner motd
show ip interface brief
show running-config
```

## What I Learned

This lab introduced the basic configuration process for Cisco routers and switches. I learned how to assign hostnames, secure device access with passwords, configure router interfaces with IPv4 addresses, create management access for switches, and verify connectivity using show commands and ping tests.
