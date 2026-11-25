# Configure IPv6 Addresses on Network Devices

## Objective

Configure IPv6 addressing on Cisco routers, switches, and hosts. Verify IPv6 connectivity using SLAAC, link-local addresses, and IPv6 troubleshooting commands.

## Skills Practiced

- IPv6 Address Configuration
- Global Unicast Addressing
- Link-Local Address Configuration
- IPv6 Routing
- SLAAC (Stateless Address Autoconfiguration)
- IPv6 Verification and Troubleshooting
- IPv6 Connectivity Testing

## Key Commands

```cisco
ipv6 unicast-routing

interface g0/0/0
ipv6 address 2001:db8:acad:a::1/64
ipv6 address fe80::1 link-local

interface g0/0/1
ipv6 address 2001:db8:acad:1::1/64
ipv6 address fe80::1 link-local

show ipv6 interface brief
show ipv6 interface
show ipv6 route

ping
tracert
```

## What I Learned

This lab demonstrated how IPv6 addressing works on Cisco devices. I learned how to configure global unicast and link-local addresses, enable IPv6 routing, use SLAAC for automatic host addressing, verify IPv6 connectivity, and troubleshoot IPv6 networks using Cisco IOS verification commands.
