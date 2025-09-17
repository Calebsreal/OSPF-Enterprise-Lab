# OSPF-Enterprise-Lab

##Lab Overview :
Cisco Packet tracer lab that connects two networks using OSPF. Each network contains three VLANs/subnets, designed with VLSM for efficient IP addressing. The lab demonstrates inter-VLAN routing, ROAS, Layer 3 switch SVIs , and OSPF configuration.

##Skills Demonstrated : 
-VLAN creation and port assignment
-Subnetting using VLSM
-Router-on-a-Stick configuration
-Layer 3 switch SVIs for inter-VLAN routing
-OSPF configuration with passive interfaces
-Verification of end-to-end connectivity using ping

##Mistakes / Troubleshooting :
While conducting this lab I ran into an issue at one point that I couldn't get 2 routers to establish OSPF adjacency. I reviewed my configurations and saw that the wildcard mask for a specific network was incorrect. After correcting the wildcard mask, OSPF connectivity was successfully established and the network functioned as intended.

##How to open :
Download the .pkt file and open in Cisco Packet Tracer
