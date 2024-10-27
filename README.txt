Prerequisites:
1.Cisco Packet Tracer

Steps to run the file:
1.Open the Packet Tracer File
2.Review the Network Topology
3.Verify Device Configurations
4.Test Connectivity
5.Verify Security Configurations

Troubleshooting:
1.Recheck the IP addressing and VLAN configurations.
2.Ensure that all devices are powered on and correctly connected.
3.Review the routing table to verify routes are being advertised correctly.



Project Overview
Kalinga Health Services is a leading health provider in Bhubaneshwar,operating two hospital locations within the city.
This project outlines the design and implementation of a secure and efficient network infrastructure to support the institution's operations.

Locations
Headquarters (HQ)
Branch Hospital (BH)

Departments of HQ:
Medical Lead Operation & Consultancy Services (MLOCS)
Medical Emergency and Reporting (MER)
Medical Records Management (MRM)
Information Technology (IT)
Customer Service (CS)

Departments of BH:
Nurses & Surgery Operations (NSO)
Hospital Labs (HL)
Human Resource (HR)
Marketing (MK)
Finance (FIN)

Design consists of:
1.Cost-effective and secure network infrastructure.
2.Ownership of Local Area Network (LAN), Wide Area Network (WAN), and server-side site.
3.Compliance with the CIA triad (Confidentiality, Integrity, Availability).
4.Hierarchical network model with redundancy.
5.Separate network segments for each department.
6.Hierarchical model with core routers at HQ and Branch.
7.Separate VLAN and subnetwork for each department

IP Addressing
Base network: 192.168.100.0
Public static IP addresses connected to ISPs:
195.136.17.0/30
195.136.17.4/30
195.136.17.8/30
195.136.17.12/30

Device Configuration:
1.Basic device settings (hostnames, passwords, etc.) configured.
2.Inter-VLAN routing enabled on multilayer switches.
3.DHCP servers for dynamic IP allocation.
4.Static IP addresses for server room devices.

Security Measures:
1.Implemented Access Control Lists (ACLs) for user access control.
2.Configured site-to-site IPSec VPN for secure communication between HQ and Branch.
3.SSH enabled for secure remote access to devices.
4.Port security configured on switches to control device connectivity.

Routing Protocol:
1.OSPF used for route advertisement on routers and multilayer switches.
2.Default static routing configured for handling unmatched traffic.