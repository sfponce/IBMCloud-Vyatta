# IBMCloud-Vyatta

Mergeable Vyatta/Brocade5600 configs for IBM Cloud. Two data centers LON06 and AM01 connected via IPSec VPN over 
public network. Static routing, NAT and Firewalls to allow communication between two APP zones on private VLANs. 
VIF for dp0bond0.<Private VLAN> to be added to interfaces section, plus updates to static routing and VPN section 
for site-to-site peersfor different environments. 
