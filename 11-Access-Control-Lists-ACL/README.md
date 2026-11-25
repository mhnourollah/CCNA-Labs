# Access Control Lists (ACL)

## Objective

Understand how Access Control Lists (ACLs) can be used to filter network traffic and control access between local and remote networks.

## Skills Practiced

- Standard ACL Configuration
- Traffic Filtering
- Interface ACL Application
- Inbound and Outbound ACL Processing
- ICMP Filtering
- Connectivity Testing
- ACL Verification and Troubleshooting

## Key Commands

```cisco
access-list 11 deny 192.168.10.0 0.0.0.255
access-list 11 permit any

interface serial 0/0/0
ip access-group 11 out

show access-lists
show running-config | include interface|access

no ip access-group 11 out
no access-list 11
```

## What I Learned

This lab demonstrated how ACLs can be used to control network traffic by permitting or denying packets based on source addresses. I learned how ACLs are applied to router interfaces, how they affect connectivity between networks, and how to verify and troubleshoot ACL operations using show commands.
