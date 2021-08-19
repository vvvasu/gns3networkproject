# gns3networkproject
University Network: 

We have taken a small university network as our network scenario. A university called “MDBW” has its own network with 4 VLANS. 
It has 2 departments which are Computing department and Admin department in the main network and 2 Marketing offices in 2 different locations. 
Those marketing offices has only one VLAN for each. We have 2 leased line cables from ISP to connect Main campus and Marketing offices. 
We will be using Star Topology for this scenario with use of Switching network and Virtual Local Area Networks.

Main Router: Main Campus
192.168.1.0/24 – Directly connected to marketing office 1
Marketing Office (1): VLAN 10 – 10.10.10.0/29 (255.255.255.248 WC: 0.0.0.7) Available hosts 6
Truncated the VLAN in to use only 6 hosts, since the marketing office end hosts requirements are less.
192.168.2.0/24 – Directly connected to marketing office 2
Marketing Office (2): VLAN 20 – 10.10.20.0/29 (255.255.255.248 WC: 0.0.0.7) Available hosts 6
Main Switch: Core Switch (4 VLANS, VLAN 100,200,300,400)
Faculty of Computing
Computing_LAB
VLAN 100 (10.10.30.0/27 255.255.255.224 WC: 0.0.0.31 host 30)
Computer LAB has only 25 PCS, therefore truncated the 10.10.30.0 network with 255.255.255.224 mask which is 30 hosts.
Computing_EXAM
VLAN 200 (10.10.40.0/27 255.255.255.224 WC: 0.0.0.31 host 30)
Administration
Admin_HR
VLAN 300 (10.10.50.0/28 255.255.255.240 WC: 0.0.0.15 host 14)
Admin_Finance
Finance department requires only 12 PCS, therefore truncated the 10.10.60.0 network with 255.255.255.140 mask which is 14 hosts.
VLAN 400 (10.10.60.0/28 255.255.255.240 WC: 0.0.0.31 host 14)

The complete university area has been made of four VLAN networks.
These VLAN networks are distributed to the following departments
• Computing Lab - VLAN100
• Computing Exam - VLAN200
• HR Department - VLAN300
• Finance Department - VLAN400
