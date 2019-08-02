1
NETWORKING IN UNIVERSITY PROJECT REPORT
NATIONAL UNIVERSITY OF COMPUTER AND EMERGING SCIENCES

2
Contents
1- Abstract
2- Network Requirements 3- Features And Services
4- Network Topology Diagram
5- Network Topology Explanation 6- Summary
3
1 Abstract:
The project is to design a topology of university network using Cisco packet tracer with a complete implementation of dhcp via routers This University Network consist the following devices.
1- Layer 2 Switches
2- Layer 3 Routers
3- DNS / FTP and Email Server 4- Printer
5- HTTPS
6- Vlan
7- SSH
8- Telnet
9- SMTP
The design includes the following department in university. 1- CS Departments
2- EE and BBA Department 3- Library
4- IT Department
2 Network Requirements
This university network has the following requirements:
Department:
This university design has three Department CS , EE and BBA, IT Department and Library. Both CS and EE has 300 hosts 3 labs and a faculty Department each. IT Departments has 25 hosts. Moreover Library has 200 hosts and a printer in each department.
Email service:
An email service is provided in an IT Department which will be used for communication between all 4 departments.
DNS service:
A DNS server is provided in an IT Department for university website.
4
3 Features And Services
According to the design requirements, the university network design provides the following features and services:
VLSM ( Variable Length Sub-net Masking ):
There are four departments and each department is connected to a different network.
DHCP ( Dynamic Host Configuration Protocol ) Servers:
DHCP pool is created and the service for every department is provided through router. It provides dynamic IP Address allocation through which a host can connects to the network.
FTP ( File Transfer Protocol ) Server:
There is a FTP server in the IT Department that will provide the FTP service across all department throught out the network.
DNS ( Domain Name System ) Server:
The DNS server in the IT Department that will provide website service in all departments of university.
SSH secured routers:
The routers are secured with ssh.
Email Server:
The Email server in the IT Department that will allow all departments to communicate with each other.
RIP V2 ( Routing Information Protocol) Routing Protocol:
All the routers are configured with RIP version2 because they support VLSM.
VLAN( Virtual Local Area Network ):
Virtual Local Area Network have been implemented so that the labs in a departments are kept separated, each department is assignment different number of hosts.
5
4 Network Topology Diagram
The following figure for the university network in Cisco Packet Tracer is shown below.
6
5 Network Topology Explanation:
The network shown in the figure shows the university network in Cisco Packet Tracer.
Departments:
There are 4 departments in this university network with a network 129.12.0.0 . The CS Department has 3 labs with 80 host on each lab , 1 research lab with 120 host and 1 faculty room with 45 hosts.
The EE and BBA is a single department with network 129.14.0.0 which has 3 labs with 80 host on each lab, and 1 faculty room with 45 host. Library building with network
129.13.0.0 has been provided with 200 hosts. IT Departments with network 129.15.0.0 has been provided with the 25 host, and the printer service has been provided to all departments.
DNS , FTP and Email Server:
The single server is provided with all three service located in the IT Department and pro- viding services to all other Departments. It hosts the university’s website.
SSH on each router
Each router in a university network is protected with SSH.
6 Summary
This whole university network is designed with all the fundamental requirements provided in the university. The university has four departments with each of them are connected to the main central router providing connection to each department and can communicate with each other as well as with the administration. This network has been provided with all the fundamental concepts that we have been taught in the lab such as VLSM, Sub-netting, Routing, DHCP pool routing configuration, DNS, FTP, Email, and SSH.
