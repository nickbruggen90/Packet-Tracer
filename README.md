# Packet-Tracer examples
SOHO set-up using EtherChannel:
<a href="https://drive.google.com/file/d/1UlAXGKmIirPDxHGWzG7X3EaeZSxKxEfh/view?usp=share_link">pkt file</a>
Guidelines:
1) PC 0,2 in VLAN20 using 10.67.83.16/28
   PC 1,3 in VLAN30 using 10.67.83.0/28
2) DHCP/DNS server in VLAN10 using 10.67.83.32/28
   DHCP assigned IP's to end-clients
3) Default gateway needs to be first IP in subnet
4) Use etherchannel

Steps:
1) Configure the switch/router (these-LINK)
2) Create the VLANs
3) Trunk switches
4) No shutdown router
5) Create subinterfaces within router
6) Create DHCP relay
7) Create DHCP scope
8) Check clients are getting DCHP assigned IP's
