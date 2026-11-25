# Configure NAT for IPv4

## Objective

Configure and verify different types of Network Address Translation (NAT) on Cisco routers, including Dynamic NAT, PAT (NAT Overload), and Static NAT.

## Skills Practiced

- Dynamic NAT
- NAT Pools
- Port Address Translation (PAT)
- NAT Overload
- Static NAT
- Access Control Lists (ACLs)
- NAT Verification and Troubleshooting

## Key Commands

```cisco
access-list 1 permit 192.168.1.0 0.0.0.255

ip nat pool PUBLIC_ACCESS 209.165.200.226 209.165.200.228 netmask 255.255.255.248

ip nat inside source list 1 pool PUBLIC_ACCESS

ip nat inside source list 1 pool PUBLIC_ACCESS overload

ip nat inside source list 1 interface g0/0/0 overload

ip nat inside source static 192.168.1.2 209.165.200.229

show ip nat translations
show ip nat statistics
```

## What I Learned

This lab demonstrated how private IPv4 addresses can be translated into public addresses using Dynamic NAT, PAT, and Static NAT. I learned how PAT conserves public IPv4 addresses by allowing multiple devices to share a single public address through port numbers, while Static NAT provides a permanent one-to-one mapping between private and public addresses.
