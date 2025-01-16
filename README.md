# CCNA Project: Network Configuration Using Cisco Packet Tracer

This project demonstrates the implementation of a network configuration based on the CCNA curriculum. The project was completed using Cisco Packet Tracer, and the configurations are based on the requirements outlined in the provided PDF document.

## Project Overview

The project involves the following tasks:

1. **Building the Network Topology:**
   - The network topology was built as per the provided figure.
   - Basic configurations were applied to switches and routers, including hostnames, domain names, and password encryption.

2. **VLAN Configuration:**
   - VLANs 10, 20, and 30 were created on Switch 1 (S1).
   - VLANs 40, 50, and 60 were created on Switch 2 (S2).
   - Interfaces were assigned to the respective VLANs, and Rapid Spanning Tree Protocol (STP) was enabled on all switches.

3. **DHCP Configuration:**
   - DHCP pools were configured on the router to distribute IP addresses to all end devices in the network.
   - Each VLAN was assigned a unique subnet, and the default router and DNS server were specified.

4. **Routing Configuration:**
   - A dynamic routing protocol (EIGRP) was used to configure routing between three routers.
   - Two routers were connected using a serial cable, and a default route was configured.

5. **ACL Configuration:**
   - Access Control Lists (ACLs) were implemented to restrict access to specific services.
   - For example, a host was denied DNS services, and a network was prevented from accessing a web server.

6. **Additional Configurations:**
   - A RADIUS server was added to the network for default authentication.
   - Mail server configurations were implemented, and ACLs were used to restrict VLAN 10 from accessing mail services.

## Repository Contents

- `Project-CCNA.pdf`: The project requirements and instructions.
- `fINAL_PROJECT.pkt`: The Cisco Packet Tracer file containing the network topology and configurations.

## How to Use This Repository

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/your-username/CCNA-Project.git
