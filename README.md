# Network Engineering & Administration Lab Portfolio

Welcome to my networking lab portfolio. This repository showcases a collection of hands-on labs that demonstrate my skills in network design, configuration, and troubleshooting using Cisco Packet Tracer.

## About This Portfolio

The purpose of this portfolio is to provide tangible evidence of my abilities in key areas of network administration. Each project covers foundational concepts, from physical layer connectivity to advanced routing and switching. All labs were built, configured, and verified in a simulated environment.

---

## Skills Demonstrated

Across these labs, I have gained and demonstrated proficiency in the following areas:

* **Network Fundamentals:** OSI Model, TCP/IP Suite (TCP & UDP), IPv4/IPv6 Addressing, and Subnetting.
* **Switching Technologies:**
    * Creating and managing VLANs to segment networks for improved security and performance.
    * Configuring 802.1Q trunk ports to carry traffic for multiple VLANs between switches.
* **Routing Protocols & Configuration:**
    * Implementing "Router on a Stick" for Inter-VLAN routing.
    * Configuring static and default routes (`0.0.0.0/0`) to connect different networks.
    * Basic router setup, including IP addressing and interface configuration.
* **IP Services:** Differentiating between and applying static and dynamic (DHCP) IP addressing schemes.
* **Troubleshooting:**
    * Verifying connectivity and network paths using `ping` and `traceroute`.
    * Using Cisco IOS `show` commands (`show ip interface brief`, `show vlan`, `show ip route`) to validate configurations.

---

## Lab Summaries

Here is a brief overview of the concepts applied in each lab. You can find detailed documentation and screenshots in their respective folders.

### Lab 2: OSI Model & Cabling
Analyzed the 7 layers of the OSI model and demonstrated physical layer connectivity. This involved creating network cables (patch and crossover) and establishing a direct PC-to-PC link, verified with `ping`.

### Lab 3: Local Area Network (LAN) Configuration
Designed and configured a basic small office network topology. A Cisco router was set up as the default gateway, connecting multiple end-devices through a multilayer switch.

### Lab 4: VLANs and Trunking
Implemented network segmentation by creating multiple VLANs. Configured an 802.1Q trunk port to extend the VLANs across two switches, ensuring traffic was properly isolated.

### Lab 5: Inter-VLAN Routing
Configured Inter-VLAN routing using the "Router on a Stick" method. A single physical router interface was divided into multiple logical sub-interfaces, enabling communication between previously isolated VLANs.

### Lab 6: Static Routing
Established connectivity between two separate networks using static routes. A default route (`0.0.0.0/0`) was configured to serve as the gateway of last resort, directing all non-local traffic to the correct next-hop address.

### Lab 8: IPv6 Implementation
Demonstrated proficiency with IPv6 by configuring interfaces with 128-bit addresses. This lab covered IPv6 address abbreviation and its key advantages over IPv4, such as a vastly larger address space.
