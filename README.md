# Cisco Packet-Tracer Lab - Router/VLAN Configuration using the CLI   💻🔌

## Objective
✨ To construct and configure a basic network topology utilizing routers and VLANs in Cisco Packet Tracer, employing Command Line Interface (CLI) commands to implement VLAN segmentation and inter-VLAN routing. The objective is to provide hands-on experience in creating a simple network infrastructure and understanding the fundamentals of network communication for small to medium-sized businesses.


### Skills Learned

- Ability to send ICMP packets to another device on the network.
- Understanding of LAN and the assignment of static and dynamic IP assignment. 
- Configuration of IP, subnet, and gateway addresses for endpoints.
- Ability to segment vlans for each department.


## Steps

✨ LAB NAME: Small Network Connectivity using routers.

✨ OBJECTIVE: The aim is to configure a simple network to allow connectivity for sending and receiving packets.

✨ THEORY: A router will ensure the security of data and provides access to the internet.




*Ref 1: Both Endpoints with a class C IP configuration receive ping packets.

![Screenshot 2024-06-06 162509](https://github.com/nathanielreich2k/Packet-Tracer/assets/155709615/e1fff7f8-39fc-4783-9bab-2b3cb62591a2)

*Ref 2:  A Ping was sent from PC 1 to PC 2.

![ping](https://github.com/nathanielreich2k/Packet-Tracer/assets/155709615/609e2f62-8051-412b-8294-608735f87c28)




## Steps

✨ LAB NAME: VLAN Network Topolgy 

✨ OBJECTIVE: The objective is to provide hands-on experience in configuring VLANs and implementing routing between them using Cisco Packet Tracer's CLI, thus fostering a deeper understanding of network segmentation and routing principles.

✨ THEORY: Segmenting different departments and data flow will ensure proper security and communication without unauthorized interception. 


*Ref 1: Each department is assigned a static IP Address and ethernet cables connecting each PC.
![vl](https://github.com/nathanielreich2k/Packet-Tracer/assets/155709615/ebcf2770-ca03-41df-bfce-e4f3411f6e7a)



A Total of 18 PC's with 3 seperate Vlans. The objective is to allow 2 PC's in each department to talk with one another. 

*Ref 2: Using the switch CLI each port needed to be added manually, using commands such as "int" to add each port to its vlan and "switch negotiate" to enable trunking.
![VLAN](https://github.com/nathanielreich2k/Packet-Tracer/assets/155709615/4c89640c-beea-41d7-9b6c-97aa809d1a31)


*Ref 3: The complete topology
![COMPLETE](https://github.com/nathanielreich2k/Packet-Tracer/assets/155709615/4754c909-ef35-4da8-8b3b-1602e6cf1bed)





























