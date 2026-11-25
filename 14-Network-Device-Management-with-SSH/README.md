# Configure Network Devices with SSH

## Objective

Configure secure remote management access to Cisco routers and switches using SSH instead of Telnet.

## Skills Practiced

- Secure Remote Management
- SSH Configuration
- RSA Key Generation
- Local User Authentication
- Device Hardening
- Secure Access Verification
- CLI Remote Connectivity

## Key Commands

```cisco
hostname R1
ip domain-name ccna-lab.com

crypto key generate rsa
1024

username admin secret Adm1nP@55

line vty 0 4
transport input ssh
login local

show ip ssh

ssh -l admin 192.168.1.1
```

## What I Learned

This lab demonstrated how to secure remote access to Cisco devices using SSH. I learned how to generate RSA encryption keys, create local user accounts, configure VTY lines for SSH-only access, and remotely manage routers and switches using encrypted communications instead of Telnet.
