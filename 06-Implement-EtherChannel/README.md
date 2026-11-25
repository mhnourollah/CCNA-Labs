# Implement EtherChannel

## Objective

Configure an EtherChannel using LACP between two Cisco switches to increase bandwidth and provide link redundancy.

## Skills Practiced

- EtherChannel Configuration
- LACP (Link Aggregation Control Protocol)
- VLAN Configuration
- Trunk Configuration
- Switch Virtual Interface (SVI) Configuration
- Port Security and Management
- Network Verification and Troubleshooting

## Key Commands

```cisco
interface range f0/1-2
channel-group 1 mode active

interface port-channel 1
switchport mode trunk
switchport trunk native vlan 99
switchport trunk allowed vlan 20,99

show etherchannel summary
show interfaces trunk
show vlan brief
```

## What I Learned

This lab demonstrated how EtherChannel combines multiple physical links into a single logical connection. I learned how to configure LACP-based EtherChannel, create VLANs, configure trunk links, and verify redundancy and connectivity between switches using Cisco IOS verification commands.
