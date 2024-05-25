# Summary

## OSI :
There are 7 layers to the OSI model of a network that build upon each other.
seven layers:
- **Physical Layer**: Deals with the physical connection between devices.
- **Data Link Layer**: Handles error detection, correction, and frames.
- **Network Layer**: Manages data routing, forwarding, and addressing.
- **Transport Layer**: Ensures complete data transfer with protocols like TCP and UDP.
- **Session Layer**: Manages sessions and connections.
- **Presentation Layer**: Translates data formats.
- **Application Layer**: Provides network services to end-users.

## TCP/IP :
TCP is a connection-oriented protocol on the transfer layer (use for security); UDP is also on the transfer layer but it’s connectionless (use for speed)
TCP ports use digital identifiers to identify the right type of process for a command.
It has four layers:
- **Link Layer**: Combines OSI's Physical and Data Link layers.
- **Internet Layer**: Corresponds to OSI's Network layer, dealing with IP addressing and routing.
- **Transport Layer**: Same as OSI's Transport layer, using TCP/UDP protocols.
- **Application Layer**: Merges OSI's Application, Presentation, and Session layers.

## IP Addressing :
IP addresses are necessary to use the internet. Some IP addresses are a combination of host and network; the subnet mask breaks apart which is which.
IPV4 : IPv4 addresses are 32-bit numbers and contains two primary parts—the network prefix and the host number. 
IPV6 : IPv6 is a 128-bits address and consists of eight groups of four hexadecimal digits.

There are 5 classes of IP addresses, each with different lengths for prefixes and a predetermined amount of addresses under that class.
Classless Interdomain Routing (CIDR) is a solution to the problem of non-ideal numbers of IP addresses—by removing classes, it removes the need for specific caps on totals.

## Routing :
Routing is the process of sending information over a network. It involves determining the path for data to travel from source to destination across networks.
Key protocols include:
- **RIP (Routing Information Protocol)**
- **OSPF (Open Shortest Path First)**
- **BGP (Border Gateway Protocol)**

## Subnetting :
Subnetting divides an IP network into smaller sub-networks to improve routing efficiency and network management. 

## DHCP : 
Dynamic Host Configuration Protocol automates the assignment of IP addresses, subnet masks, and other network settings to devices on a network.

## DNS :
The DNS network translates computer language to human language and gives names to domains across the network. You can do lookups to find the IP address associated with a certain DN. Domains are owned, but an owner can delegate certain parts to new owners.

## NAT :
Network Address Translation translates private IP addresses to a public IP address for accessing the internet, conserving the number of public IP addresses used.

## VPN :
A Virtual Private Network extends a private network across a public network, enabling secure communication and remote access.

## Firewalls :
Firewalls are security systems that monitor and control incoming and outgoing network traffic based on predetermined security rules.

## HTTP : 
HTTP messages are plaintext, which means unauthorized parties can easily access and read them over the internet. HTTP allows you to interact with web pages, files, etc. on a network. It works by sending out a certain type of command/request. In return, you can get a response code that tells you the status of your request. 

## HTTPS : 
HTTPS transmits all data in encrypted form. When users submit sensitive data, they can be confident that no third parties can intercept the data over the network.

## SSL/TLS :
**SSL (Secure Sockets Layer)**: A deprecated protocol for securing internet communication through encryption.
**TLS (Transport Layer Security)**: The successor to SSL, providing enhanced security and performance for secure communication over a network

## Wireless Networking :
- **Wi-Fi**: A technology for wireless local area networking with devices based on the IEEE 802.11 standards.
- **Bluetooth**: A standard for short-range wireless communication between devices.


## Network Topologies :
The arrangement of different elements (links, nodes) in a computer network. Common topologies include:
- **Bus Topology**
- **Star Topology**
- **Ring Topology**
- **Mesh Topology**

## Network Devices :
- **Router**: Directs data packets between networks.
- **Switch**: Connects devices within a single network, using MAC addresses to forward data to the correct device.
- **Modem**: Modulates and demodulates signals for data transmission over telephone lines or cable.
- **Access Point**: Allows wireless devices to connect to a wired network.

## SMTP :
Simple Mail Transfer Protocol is a protocol used for sending email messages between servers. It is a text-based protocol where one or more recipients of a message are specified and then the message text is transferred. SMTP typically operates over TCP port 25.

## FTP : 
File Transfer Protocol is a standard network protocol used to transfer files from one host to another over a TCP-based network, such as the Internet. FTP uses separate control and data connections between the client and the server and typically operates on ports 20 and 21.

## RTP : 
Real-time Transport Protocol is a protocol designed for delivering audio and video over IP networks. It is commonly used in streaming media systems, video conferencing, and push-to-talk systems. RTP works in conjunction with the RTP Control Protocol (RTCP) for monitoring data delivery.

## local host :
Localhost refers to the hostname used to access the loopback network interface of a computer, usually mapped to the IP address 127.0.0.1 in IPv4 and ::1 in IPv6. It is used for testing and development purposes as it allows network services to communicate with each other on the same machine.

## Seeder Block : 
In the context of BitTorrent, a seeder is a user who has a complete copy of the file being shared and is uploading it to other peers in the network. The term "Seeder Block" might refer to the initial group of seeders that help distribute the file to the rest of the network.

## Proxy : 
A proxy server acts as an intermediary for requests from clients seeking resources from other servers. It can be used for various purposes such as anonymity, content filtering, and improving performance by caching frequently accessed resources.

## Forward Proxy :
A forward proxy is a server that acts as an intermediary for client requests seeking resources from other servers. It sits between the client and the internet, forwarding client requests to the destination server and returning the responses to the client.

## Reverse Proxy : 
A reverse proxy is a server that sits in front of web servers and forwards client requests to the appropriate backend server. It can provide load balancing, caching, compression, and security benefits by masking the identity of the backend servers.

## CDN : 
A CDN is a system of distributed servers that deliver web content and other media to users based on their geographic location. CDNs improve the load time of websites and reduce latency by serving content from a server closest to the user.

## Apache Tomcat : 
Apache Tomcat is an open-source implementation of the Java Servlet, JavaServer Pages, and Java Expression Language technologies. It is a web server and servlet container used to run Java applications.

## Load Balancing :
Load balancing is the process of distributing network or application traffic across multiple servers to ensure no single server becomes overwhelmed. This helps improve the responsiveness and availability of applications.

## F5 Load Balancer : 
F5 Load Balancer is a product from F5 Networks that distributes network or application traffic across multiple servers. It improves the availability, reliability, and performance of applications by balancing the load and providing redundancy.

## Palo alto network dashboard : 
Palo Alto Networks provides network security solutions, and their dashboard is a web-based interface used for monitoring and managing network security appliances. It offers visibility into network traffic, threat prevention, and policy management.

## Secure Pulse :
Pulse Secure is a company that provides secure access solutions. "Secure Pulse" likely refers to their suite of products designed to provide secure remote access to corporate networks and applications, including VPNs and Zero Trust network access solutions.
