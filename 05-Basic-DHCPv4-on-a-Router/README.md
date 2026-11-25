# Configure Basic DHCPv4 on a Router

## Objective

Configure a Cisco router as a DHCPv4 server to automatically assign IP addresses and network settings to clients on multiple LANs.

## Skills Practiced

- DHCPv4 Configuration
- DHCP Address Pools
- Excluded Addresses
- DNS Configuration
- Lease Configuration
- Automatic IP Address Assignment
- DHCP Verification and Troubleshooting

## Key Commands

```cisco
ip dhcp excluded-address
ip dhcp pool
network
default-router
dns-server
domain-name
lease 7
show ip dhcp binding
show run | section dhcp
ipconfig /all
ipconfig /renew
```

## What I Learned

This lab demonstrated how to configure a Cisco router as a DHCPv4 server. I learned how to create DHCP pools, reserve addresses for network devices, provide DNS and default gateway information to clients, verify DHCP bindings, and troubleshoot address assignment issues.
