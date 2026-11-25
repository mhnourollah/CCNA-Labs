# Basic OSPF Configuration

## Objective

Configure and verify single-area OSPF routing between multiple Cisco routers to enable dynamic route exchange across the network.

## Skills Practiced

- OSPF Configuration
- OSPF Neighbor Relationships
- OSPF Router ID Configuration
- Loopback Interfaces
- OSPF Cost Manipulation
- Default Route Advertisement
- OSPF Timer Configuration
- Route Verification and Troubleshooting

## Key Commands

```cisco
router ospf 1

network 172.16.1.16 0.0.0.15 area 0
network 10.10.10.0 0.0.0.255 area 0
network 192.168.10.0 0.0.0.3 area 0

router-id 10.1.1.1

show ip ospf neighbor
show ip ospf
show ip protocols
show ip route

default-information originate

ip ospf hello-interval 5
ip ospf dead-interval 20
```

## What I Learned

This lab demonstrated how OSPF dynamically exchanges routing information between routers. I learned how to establish OSPF neighbor adjacencies, configure router IDs using loopback interfaces, advertise networks within Area 0, adjust OSPF costs and timers, and propagate default routes throughout an OSPF network.
