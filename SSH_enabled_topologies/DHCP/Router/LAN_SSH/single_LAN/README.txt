# Cisco Lab – Single LAN with SSH Configuration

## Description
This project demonstrates the configuration of a Cisco 2811 router with:
- A single LAN
- SSH for secure remote management
- Encrypted passwords for enhanced security

The lab validates:
1. Router interface configuration with IP address
2. Secure SSH access to the router
3. Password encryption for local user accounts

## Tools Used
- Cisco Packet Tracer (simulation)
- Cisco 2811 Router
- PCs/Hosts for SSH client testing
- Cisco IOS CLI commands

## Learning Takeaways
- Configure router interfaces with IP addresses
- Setup SSH using domain name and RSA key generation
- Create local users with encrypted secrets
- Secure remote access using:
  - ssh -l <username> <router-ip>
- Use "show" commands for verification:
  - show running-config
  - show ip ssh
  - show ssh

## Folders Included
configs/       -> Router configuration file (single LAN with SSH)
topology/      -> Packet Tracer (.pkt) single LAN topology
screenshots/   -> CLI outputs (show run, show ssh, SSH login test)
docs/          -> Setup guide and notes
