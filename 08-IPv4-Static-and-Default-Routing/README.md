# Configuring IPv4 Static and Default Routes

## Objective

Configure and verify IPv4 static routes and default routes between multiple networks using Cisco routers.

## Skills Practiced

- Static Routing
- Default Routing
- Next-Hop Static Routes
- Directly Connected Static Routes
- Routing Table Verification
- Serial Interface Configuration
- Loopback Configuration
- Network Troubleshooting

## Key Commands

```cisco
ip route 192.168.20.0 255.255.255.0 10.1.1.2
ip route 192.168.10.0 255.255.255.0 s0/0/0

ip route 0.0.0.0 0.0.0.0 s0/0/1
ip route 0.0.0.0 0.0.0.0 lo0

show ip route
ping
```

## What I Learned

This lab demonstrated how routers communicate with remote networks using static routes. I learned the difference between next-hop and directly connected static routes, how default routes provide a path for unknown destinations, and how to verify routing decisions using routing tables and connectivity tests.
