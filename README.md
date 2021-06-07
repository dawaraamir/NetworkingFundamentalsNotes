# NetworkingFundamentalsNotes
- DNS (domain name systems) have two types of servers: recrusive and authoratative. Recrusive takes time to cache the records as it needs to talk to multiple authoritative servers hence why when we try to update our web apps it takes time to see the new updates. 
- Ports are part of TCP(Transmission Control Protocol) which are used on top of IP to ensure reliable transmission of packets and UDP (User Datagram Protocol) is a communications protocol that is primarily used for establishing low-latency and loss-tolerating connections between applications on the internet. When you send a TCP message you want it to get the specifc program, ex. requesting a webpage but getting back a mailing service would be a bad request as each program needs to be on its on port. 
- Peer to peer network all nodes are equal and any node can talk to any other node. No node has any special role. This was the original networking model of windows networking.
- The OSI Model (Open Systems Interconnection Model) is a conceptual framework used to describe the functions of a networking system. The communications between a computing system are split into seven different abstraction layers: Physical, Data Link, Network, Transport, Session, Presentation, and Application.
Physical: transmits raw bit stream over physical medium.
Data Link: Defines the format of data on network
Network: Decideds which physical path the data will take
Transport: Transmits the data using trasnmission protocols (TCP UDP)
Session: Maintains connections and is responsible for controlling ports and sessions
Presentation: Ensures data is in usable format and where encryption occurs
Application: Human-computer interaction, app can access network services
- Protocol is just the language that the two applications on either end of a conversation agree to speak in. A port is like a phone extension, with the computer's IP address being like its phone number. You can call the number (IP address) to talk to the computer, then dial the extension (port) to talk to a specific application.
- HTTPS is HTTP with encryption. The only difference between the two protocols is that HTTPS uses TLS (SSL) to encrypt normal HTTP requests and responses. As a result, HTTPS is far more secure than HTTP.
- Hexadecimal (or hex) is a base 16 system used to simplify how binary is represented. This means an 8-bit binary number can be written using only two different hex digits - one hex digit for each nibble (or group of 4-bits).
- An IP address is a unique address that identifies a device on the internet or a local network. IP stands for "Internet Protocol," which is the set of rules governing the format of data sent via the internet or local network. Types include consumer, private, public, dynamic, and static which can be be further broken into shared or dedicated web ip adresses.
- Subnetting ensures that traffic destined for a device within a subnet stays in that subnet, which reduces congestion. Through strategic placement of subnets, you can help reduce your network's load and more efficiently route traffic.
- IPv6 is the “next generation” of IP, which provides a vastly expanded address space. Using IPv6, the Internet will be able to grow to millions of times its current size, in terms of the numbers of people, devices and objects connected to it.
- A virtual local area network (VLAN) is a logical group of workstations, servers and network devices that appear to be on the same LAN despite their geographical distribution. ... The purpose of implementing a VLAN is to improve the performance of a network or apply appropriate security features.
- IP Routing is an umbrella term for the set of protocols that determine the path that data follows in order to travel across multiple networks from its source to its destination. Data is routed from its source to its destination through a series of routers, and across multiple networks.
-- Bus network topology: Also known as backbone network topology, this configuration connects all devices to a main cable via drop lines. 
-- Mesh network topology: A dedicated point-to-point link connects each device on the network to another device on the network, only carrying data between two devices. 
Ring network topology: Two dedicated point-to-point links connect a device to the two devices located on either side of it, creating a ring of devices through which data is forwarded via repeaters until it reaches the target device. 
Star network topology: The most common network topology, star topology connects each device in the network to a central hub. Devices can only communicate with each other indirectly through the central hub. 
Hybrid network topology: Any combination of two or more topologies is a hybrid topology. 
Tree network topology: This topology consists of a parent-child hierarchy in which star networks are interconnected via bus networks. Nodes branch out linearly from one root node, and two connected nodes only share one mutual connection.
- Dynamic Host Configuration Protocol (DHCP) is a network management protocol used to automate the process of configuring devices on IP networks, thus allowing them to use network services such as DNS, NTP, and any communication protocol based on UDP or TCP.
- 3 types of DNS servers: DNS Resolver, DNS Root Server and Authoritative Name Server.
