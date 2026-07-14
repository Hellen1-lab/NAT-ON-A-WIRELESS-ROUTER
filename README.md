# NAT-ON-A-WIRELESS-ROUTER

Packet Tracer Lab: Examine NAT on a Wireless Router


##OVERVIEW


This lab focused on understanding how Network Address Translation (NAT) works on a wireless router. I configured devices to receive IP addresses through DHCP, examined both private and public IP addresses, and observed how the router translated private IP addresses into a public IP address for communication over the Internet.


##OBJECTIVES

Examine NAT configuration on a wireless router.

Configure PCs to obtain IP addresses using DHCP.

Identify private and public IP addresses.

Observe NAT translation using Simulation Mode.

Analyze packet headers before and after NAT.

##TOOLS USED

Cisco Packet Tracer

##KEY CONCEPTS LEARNED

DHCP automatically assigns IP addresses to devices on the network.

Private IP addresses (e.g., 192.168.1.100) are used within a local network and cannot be routed on the Internet.

Public IP addresses are assigned by an ISP and are used for communication over the Internet.

NAT translates private IP addresses into a public IP address, allowing internal devices to access external networks securely.

The router maintains a NAT table to ensure responses from external servers are delivered to the correct internal device.


##RESULTS

Successfully configured the PC to obtain an IP address via DHCP.

Verified the router's public IP address assigned by the ISP.

Observed the local network using private IP addresses.

Captured and analyzed packet headers before and after NAT translation.

Confirmed that the source IP changed from a private IP address to the router's public IP address while the destination IP remained unchanged.


##SKILLS DEMONSTRATED

Network configuration.

DHCP.

Network Address Translation(NAT).

Packet analysis.

Cisco Packet Tracer.

Networking fundamentals.
