# Switch Port Security Challenge

## Objective

Implement switch port security, VLANs, trunking, inter-VLAN routing, and DHCP services to create a secure and functional enterprise network.

## Skills Practiced

- Switch Port Security
- Sticky MAC Address Learning
- VLAN Configuration
- Trunk Configuration
- Inter-VLAN Routing
- DHCPv4 Configuration
- PortFast Configuration
- BPDU Guard
- Network Verification and Troubleshooting

## Key Commands

```cisco
switchport port-security
switchport port-security maximum 2
switchport port-security mac-address sticky

spanning-tree portfast
spanning-tree bpduguard enable

show port-security interface
show spanning-tree interface detail
show vlan brief

ip dhcp pool
ip dhcp excluded-address
```

## What I Learned

This lab demonstrated how switch port security protects access ports from unauthorized devices using sticky MAC address learning and secure address limits. I also learned how PortFast and BPDU Guard help protect the network from switching loops while maintaining fast host connectivity. The lab combined VLANs, inter-VLAN routing, DHCP, and security features into a single integrated network solution.
