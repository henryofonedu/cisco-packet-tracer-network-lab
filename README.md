# Cisco Packet Tracer Network Lab

A Cisco Packet Tracer network lab implementing multiple LANs, DHCP, DNS, HTTP/Web Server services, and inter-network routing with connectivity and packet-flow verification.

## Project Overview

This project was built to reinforce my understanding of networking after completing the Networking Basics course on Cisco Networking Academy.

The lab was designed to simulate a small network environment where different networks communicate through a router while providing basic network services such as DHCP, DNS, and a Web Server.

## Project Objectives

* Configure multiple LAN networks connected through a router.
* Configure the router to provide DHCP services.
* Configure a DNS server for domain name resolution.
* Configure a Web Server to host a webpage.
* Allow devices to communicate across different networks.
* Test and verify network connectivity.
* Observe DNS and HTTP packet flow using Simulation Mode.

## Network Components

The network includes:

* Router
* DNS Server
* Web Server
* PCs and other end devices
* Multiple LAN networks

## Services Implemented

### DHCP

The router was configured as a DHCP server so that end devices could automatically obtain their:

* IP address
* Subnet mask
* Default gateway
* DNS server information

This removed the need to manually configure the network settings on each client device.

### DNS

A DNS server was configured to resolve the domain name:

`www.henrysite.com`

to the IP address of the Web Server.

This allowed clients to access the website using a domain name instead of having to enter the server's IP address.

### Web Server

A Web Server was configured to host a webpage.

Client devices were able to access the webpage using both:

* The Web Server's IP address
* `www.henrysite.com`

## Network Connectivity

The router connects the different LANs and allows devices on separate networks to communicate.

Connectivity was verified by:

* Pinging default gateways
* Pinging devices on other networks
* Testing communication between client devices
* Confirming that a home laptop could successfully ping PC3

## Verification and Testing

### 1. DHCP Configuration

End devices successfully received their network configuration automatically from the router.

### 2. DNS Resolution

The DNS server successfully resolved `www.henrysite.com` to the Web Server's IP address.

### 3. Web Server Access

Client PCs successfully accessed the hosted webpage using both the server IP address and the domain name.

### 4. Inter-Network Routing

Devices on different LANs successfully communicated through the router.

### 5. Default Gateway Verification

Devices successfully pinged their default gateways, confirming that the gateway configuration was working correctly.

### 6. Packet Flow Analysis

Cisco Packet Tracer's Simulation Mode was used to observe DNS and HTTP packets travelling between the client and Web Server.

## Screenshots

### Network Topology

![Network Topology](https://github.com/henryofonedu/cisco-packet-tracer-network-lab/blob/main/screenshots/network%20topology.jpg?raw=true)

### DHCP Verification

![DHCP Verification](https://github.com/henryofonedu/cisco-packet-tracer-network-lab/blob/main/screenshots/pc1%20getting%20ip%20address%20successful.jpg?raw=true)

### DNS Resolution

![DNS Resolution](screenshots/dns.png)

### Web Server Access

![Web Server Access](screenshots/web-server.png)

### Connectivity Test

![Connectivity Test](screenshots/connectivity-test.png)

### Packet Flow Analysis

![Packet Flow Analysis](screenshots/packet-flow.png)

## Technologies Used

* Cisco Packet Tracer
* DHCP
* DNS
* HTTP/Web Server
* IP Networking
* Routing
* ICMP/Ping
* Simulation Mode

## Key Concepts Practiced

* IP addressing
* DHCP
* DNS
* Default gateways
* Inter-network communication
* Routing
* Web services
* Network connectivity testing
* Packet analysis

## What I Learned

This project helped me move beyond just learning networking concepts theoretically and gave me practical experience configuring and testing a network.

I gained a better understanding of how DHCP automatically provides network settings, how DNS translates domain names into IP addresses, how routers allow different networks to communicate, and how clients interact with a Web Server.

Using Simulation Mode also helped me understand how packets move through a network during DNS resolution and HTTP communication.

## Project File

The `.pkt` file included in this repository contains the Cisco Packet Tracer network lab and can be opened using Cisco Packet Tracer.
