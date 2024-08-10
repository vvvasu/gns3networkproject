# University Network Overview

In this project, we have modeled a small university network scenario. The university, named **MDBW**, operates its own network consisting of four VLANs. The network includes two main departments: the Computing Department and the Administration Department, both located on the main campus. Additionally, there are two Marketing offices situated in different locations, each with a single VLAN.

To connect the main campus with the Marketing offices, we have established two leased line connections provided by an ISP. The network topology used in this scenario is a Star Topology, incorporating Switching networks and Virtual Local Area Networks (VLANs).

## Important Notes

This GNS3 project can be run on a PC with 8GB of RAM, though this is the minimum requirement. For better performance, it is recommended to use a machine with 12GB or more of RAM.

## Network Equipment Used
- **Cisco 3745 Routers**: 4 units (with 1 router configured for NAT)
- **Cisco 3725 Routers**: 3 units (converted into Ethernet switches to demonstrate STP)
- **Default Access Switches in GNS3**: 5 units
- **Standard PCs**: 8 units
- **Cloud**

Router images can be downloaded from the GNS3 website.

## Network Methodologies Applied
- **OSPF** (Open Shortest Path First)
- **CIDR** (Classless Inter-Domain Routing)
- **VLAN** (Virtual Local Area Network)
- **STP** (Spanning Tree Protocol)
- **NAT** (Network Address Translation)
