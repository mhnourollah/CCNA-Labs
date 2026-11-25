# Configure VLANs and Inter-VLAN Routing

## Objective

Configure VLANs, trunk links, and router-on-a-stick inter-VLAN routing to enable communication between devices in different VLANs.

## Skills Practiced

- VLAN Creation and Management
- Access Port Configuration
- Trunk Configuration (802.1Q)
- Native VLAN Configuration
- Router-on-a-Stick Routing
- Inter-VLAN Communication
- Network Verification and Troubleshooting

## Key Commands

```cisco
vlan 10
vlan 20
switchport mode access
switchport access vlan 10
switchport mode trunk
switchport trunk native vlan 99
switchport trunk allowed vlan 10,20,99
encapsulation dot1Q 10
encapsulation dot1Q 20
encapsulation dot1Q 99 native
show vlan brief
show interfaces trunk
show ip route
```

## What I Learned

This lab demonstrated how VLANs separate network traffic and how trunk links carry multiple VLANs between network devices. I also learned how to configure router-on-a-stick inter-VLAN routing using router subinterfaces and 802.1Q encapsulation, allowing devices in different VLANs to communicate with each other.
