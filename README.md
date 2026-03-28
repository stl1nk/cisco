# cisco
Cisco Packet Tracer Network Project

Description

This project represents a small enterprise network model created in Cisco Packet Tracer.
The network follows a star topology with a central switch connecting end devices, IP phones, and servers.

Network Structure

The topology includes the following devices:
 • Central switch (2960-24TT)
 • Router (used for inter-VLAN routing and external connectivity)
 • Workstations (PCs)
 • IP phones (Cisco 7960)
 • Servers:
 • DNS server
 • DHCP server
 • Mail server

VLAN Segmentation

The network is logically divided using VLANs:
 • VLAN 10 (VOICE)
Used for IP telephony traffic
 • VLAN 20 (DATA)
Used for PCs and servers

Ports connected to IP phones are configured with:
 • Access VLAN 20 for connected PCs
 • Voice VLAN 10 for IP phones

Functionality
 • Automatic IP address assignment via DHCP
 • Domain name resolution using DNS
 • Email services provided by the Mail server
 • Traffic separation between voice and data networks
 • Scalable network design

Objectives
 • Understand and implement VLAN segmentation
 • Practice Voice VLAN configuration
 • Learn basic enterprise network design
 • Configure and use network services such as DHCP, DNS, and Mail

Technologies Used
 • Cisco Packet Tracer
 • VLAN (802.1Q)
 • DHCP
 • DNS
 • VoIP (IP telephony)

Project File

File format: .pkt (compatible with Cisco Packet Tracer)
