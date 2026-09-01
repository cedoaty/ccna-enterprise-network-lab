Enterprise Network Infrastructure & Security Lab
Overview
This project is an enterprise network infrastructure and security lab built using Cisco Packet Tracer. The lab demonstrates the design, configuration, implementation, and troubleshooting of a multi-device enterprise network using CCNA-level networking concepts.
The project focuses on building a functional network infrastructure that supports segmentation, routing, redundancy, address assignment, security controls, wireless connectivity, and end-to-end communication.
Objectives
The primary objectives of this project were to:
Design and implement an enterprise network topology
Configure VLANs for network segmentation
Configure 802.1Q trunking
Implement inter-VLAN routing
Configure EtherChannel for link redundancy and increased bandwidth
Implement Spanning Tree Protocol (STP)
Configure OSPF dynamic routing
Configure DHCP for automatic IP address assignment
Implement Network Address Translation (NAT)
Configure Access Control Lists (ACLs)
Configure secure remote management using SSH
Implement wireless networking
Apply network security controls
Test end-to-end connectivity
Troubleshoot network configuration and connectivity issues
Document the network architecture and configurations
Technologies & Protocols
Cisco Packet Tracer
Cisco IOS
IPv4
VLANs
802.1Q Trunking
Inter-VLAN Routing
STP
EtherChannel
OSPF
DHCP
NAT
ACLs
SSH
Wireless Networking
Network Security
Network Architecture

The network is designed using a hierarchical enterprise architecture consisting of switching, routing, wireless, and end-user components.
VLANs are used to separate network traffic into logical broadcast domains. Trunk links allow multiple VLANs to traverse the network infrastructure, while inter-VLAN routing provides communication between approved VLANs.
Layer 3 routing is implemented using OSPF to allow routers and multilayer switches to dynamically exchange routing information. EtherChannel provides redundant and aggregated links between network devices, while STP helps prevent Layer 2 switching loops.
Security controls such as ACLs and SSH are implemented to restrict unauthorized traffic and provide secure administrative access to network devices.
IP Addressing
The network uses structured IPv4 addressing to provide connectivity between VLANs, network devices, and end hosts.
VLANs
VLANs are used to logically segment the enterprise network and separate different types of devices and traffic.
Switching
The switching infrastructure includes:
VLAN configuration
Access ports
802.1Q trunking
EtherChannel
Spanning Tree Protocol
Switch management configuration
Switch configurations were verified using Cisco IOS show commands to confirm VLAN membership, trunk operation, EtherChannel status, and STP operation.
Routing
Dynamic routing is implemented using OSPF.
OSPF allows the network devices to dynamically learn and advertise routes rather than relying entirely on manually configured static routes.
Routing verification was performed using commands such as:
show ip route
show ip ospf neighbor
show ip protocols

DHCP
DHCP is used to automatically provide network configuration information to eligible client devices.
DHCP provides clients with information such as:
IP address
Subnet mask
Default gateway
DNS information
DHCP operation was verified using Cisco IOS verification commands and client connectivity testing.
Network Address Translation
NAT is used to translate private IP addresses when communication requires access to an external network.
NAT configuration and verification are included in the network documentation.
Network Security
Several security controls were implemented throughout the network.
Security measures include:
Access Control Lists (ACLs)
SSH remote management
VLAN segmentation
Device management security
Restricted network access
Port-level security configurations where applicable
The purpose of these controls is to limit unauthorized access and control how traffic moves between network segments.
Wireless Networking
Wireless networking was implemented to provide network connectivity to wireless clients.
The wireless portion of the lab demonstrates the configuration of wireless network infrastructure and client connectivity while maintaining separation from other network segments where required.
Testing & Verification
After configuration, the network was tested to verify proper operation.
Testing included:
Device-to-device ping tests
Inter-VLAN connectivity
Routing verification
OSPF neighbor verification
DHCP address assignment
VLAN verification
Trunk verification
EtherChannel verification
ACL testing
Wireless client connectivity
End-to-end network communication
Successful connectivity tests were used to confirm that the network was operating as intended.
Troubleshooting
During implementation, network configurations were tested and troubleshooting procedures were used to identify and resolve connectivity and configuration issues.
The troubleshooting process included:
Identifying the affected network segment
Checking physical and logical connectivity
Verifying interface status
Checking IP addressing
Verifying VLAN assignments
Checking trunk configuration
Verifying routing information
Checking OSPF neighbor relationships
Testing connectivity with ping
Reviewing Cisco IOS configuration and verification commands
Project Documentation
Additional project documentation can be found in the following sections:
IP Addressing
VLANs
Routing
Security
Packet Tracer File
The complete Cisco Packet Tracer project is located at:

packet-tracer/ccna-enterprise-network-lab.pkt

The Packet Tracer file contains the network topology, device configurations, addressing, routing, switching, and security configurations used throughout the project.
Project Evidence
Configuration screenshots and verification results are stored in:
screenshots/

These screenshots provide visual evidence of the network configuration and successful testing.
Key Skills Demonstrated
This project demonstrates practical experience with:
Enterprise network design
Cisco IOS configuration
Switching
Routing
VLAN implementation
Inter-VLAN routing
OSPF
DHCP
NAT
ACLs
SSH
STP
EtherChannel
Wireless networking
Network security
Network troubleshooting
Connectivity testing
Technical documentation
Infrastructure design
Conclusion
This project demonstrates the practical application of CCNA-level networking concepts in an enterprise environment. The completed infrastructure combines switching, routing, network segmentation, redundancy, dynamic routing, IP address management, wireless networking, and security controls into a single functional network.
The project also demonstrates the ability to configure Cisco devices, verify network operation, troubleshoot connectivity problems, and document an enterprise network infrastructure.
