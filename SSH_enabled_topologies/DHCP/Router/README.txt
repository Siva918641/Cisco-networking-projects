# Cisco Lab – DHCP and SSH Configuration

## Description
This project demonstrates the configuration of a Cisco 2811 router with:
- Two separate LANs
- DHCP for automatic IP allocation
- SSH for secure remote management

The lab validates:
1. End-to-end connectivity between LANs
2. Secure SSH access to the router
3. DHCP lease verification for clients

## Tools Used
- Cisco Packet Tracer (simulation)
- Cisco 2811 Router
- PCs/Hosts as DHCP clients
- Cisco IOS CLI commands

## Learning Takeaways
- Configure router interfaces with IP addresses
- Create and verify DHCP pools
- Setup SSH (domain name, RSA key generation, user authentication)
- Use "show" commands for verification:
  - show ip interface brief
  - show ip dhcp binding
  - show ip ssh
- Test LAN-to-LAN connectivity using ping

## Folders Included
configs/       -> Router configuration files
topology/      -> Packet Tracer (.pkt) topology
screenshots/   -> CLI outputs and test results
docs/          -> Setup guide and notes
