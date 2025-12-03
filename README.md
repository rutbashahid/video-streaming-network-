README.md

Project Title: Video Streaming Network Simulation (Cisco Packet Tracer)

Description:
This project demonstrates a basic video streaming network using Cisco Packet Tracer. The network contains one HTTP server, one router, two switches, and six client PCs. The purpose of this project is to simulate how multimedia traffic flows across a routed LAN. The simulation includes IP configuration, routing, ping testing, and packet flow observation in Simulation Mode.

Tools Used:

Cisco Packet Tracer (any version 7.x or 8.x)

Windows PC

Screenshots for documentation

Network Topology:
The network contains two subnets:

Subnet 1 (Server Network)
192.168.1.0/24

Subnet 2 (Client Network)
192.168.2.0/24

Insert topology screenshot here.

IP Addressing:

Server:
IP Address: 192.168.1.10
Subnet Mask: 255.255.255.0
Default Gateway: 192.168.1.1

Router:
GigabitEthernet0/0:
IP Address: 192.168.1.1
Subnet Mask: 255.255.255.0

GigabitEthernet0/1:
IP Address: 192.168.2.1
Subnet Mask: 255.255.255.0

Client PCs:
(All clients use gateway 192.168.2.1)

PC1: 192.168.2.20
PC2: 192.168.2.21
PC3: 192.168.2.22
PC4: 192.168.2.23
PC5: 192.168.2.24
PC6: 192.168.2.25

How to Run the Project:

Open the .pkt file in Cisco Packet Tracer.

Confirm the device connections and IP addresses.

On any client PC, open Desktop and then Web Browser.

Type the following in the URL bar:
http://192.168.1.10

Switch to Simulation Mode.

Select TCP in filters and click Go in the web browser.

Observe packet flow between server, router, and clients.

Insert screenshots here (browser, simulation mode, ping tests).

Testing:

Ping Tests:
Client PC → Command Prompt:
ping 192.168.2.1
ping 192.168.1.10

HTTP Test:
Open browser and type:
http://192.168.1.10

Project Folder Structure:

Video-Streaming-Network/

Video_Streaming_Network.pkt

README.md

project report
