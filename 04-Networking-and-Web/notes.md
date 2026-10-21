# Networking and Web Fundamentals

> Study notes transcribed from my personal learning document. These are works in progress, not verified technical guidance.

## HTTP commands

There are main 9  
GET:  We can use this method to retrieve a resource from web server. For example, GET https://tryhackme.com/index.php. Basically, when just tapping the web browser.  
By using inspect on the webpage then going to the network and reloading we can see things like the filename, host, scheme and such  
https://www.iamlearning.thm/contact  
the host in this www.iamlearning.thm  
the scheme would be https as it usually is  
POST  
PUT  
DELETE  
PATCH  
HEAD  
OPTIONS  
CONNECT  
TRACE  

## DNS in detail


## TLD (Top-Level Domain)

A TLD is the most righthand part of a domain name. So, for example, the tryhackme.com TLD is .com.  

## Tcp model

Ipconfig: shows the ip address the computer/pc is currently in  
There are about 65000 ports in udp transmission  

## Network fundamentals

Ping: uses ICMP (Internet control message protocol)  
How to syntax – ping Ip address  
ARP: the Address Resolution Protocol or ARP for short, is the technology that is responsible for allowing devices to identify themselves on a network.  
Simply, ARP allows a device to associate its MAC address with an IP address on the network. Each device on a network will keep a log of the MAC addresses associated with other devices.  
DHCP: Dynamic Host Configuration Protocol server. When a device connects to a network, if it has not already been manually assigned an IP address, it sends out a request (DHCP Discover) to see if any DHCP servers are on the network. The DHCP server then replies back with an IP address the device could use (DHCP Offer)  

## OSI

In the transport layer TCP(Transmission control protocol exists) used for reliability and guarantee in mind  
UDP(User datagram protocol) just cares if the data packet gets to the other place or not. It is stateless meaning a not long connection is needed to be established from points  

## Steps of DHCP(Dynamic host config process)

If you want to look up the IP address of a domain from the command line, you can use a tool such as nslookup  

## Dns types

