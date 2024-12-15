# Working-topology-using-cisco
The statements are self-Explanatory.
NOTE: You are given the network design with minimal technical documentation; your task
is to make this up and run in Cisco Packet tracer.
The following are the steps you need to perform in the topology according to the given
layout.

✓ Configure this scenario and find your given IP address in the file "IP addresses"
attached with this. Every one of you is assigned with its unique IP address. Find out
the Network Addresses and start working with them. And use them as required.

✓ Please find the number of required hosts per subnet in the same attached file. Each
student is given a different number of required hosts per subnet. Networks are
labeled alphabetically in the given file of IP ADDRESSES.

✓ Use the appropriate routing method as mentioned on the top of each block.

✓ Use Redistribution on Routers that connect two different blocks with each other.

✓ All hosts in EIGRP, OSPF area 1 & 2, and RIP will get IP addresses from the "DHCP
Server" present in the last block at the bottom.

✓ You must use VLSM in each network of the topology. Remember that between two
routers you need a total of 4 IP addresses. And information about host requirements
of all other networks is provided in the attached file as mentioned above.

✓ You must IMPLEMENT NAT in Router20 (with the Network J) & Router8 (with the
Network E). Use the Private IP Address given to you in the attached file for Nating.

✓ One of the PCs of Network A will not be allowed to access the web server. One of the
Smart Phone of Network E & Network J will not be allowed to access the Web server.

All hosts connected to network D will not be allowed to access "Web Server". (Use
ACLs on the router connected to the Web Server to enforce these restrictions.)

✓ There is a “mail server” in the first block. All the hosts will have email configured
and can send email to each other. (You have to explore this configuration by your
own)

private ip= 192.168.1.41
public ip=192.168.1.41
