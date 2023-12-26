# Computer-Network-Learning

Mastering computer basics is an important process.

## Introduction to Computer Networks

- A computer network is a set of nodes connected by communication links.
- A node can be a computer, printer or any other device capable of sending/receiving data generated by other nodes in the network.
- A communication link can be a wired link or wiredless link.
- The link carries the information.
- A computer network is mainly used for resource sharing.
- Identify end devices and intermediary devices.

## Computer Networks - Basic Characteristics

- Fault Tolerance, Scalability, Quality of Service, Security
- Fault Tolerance is the ability to continue working despite failures and to ensure no less of service
- Scalability is the ability to grow based on needs and to have good performance after growth.
- Internet is a scalable network.
- Quality of Service is the ability to set priorities and to manage data trafic to reduce data loss, delay etc.
- Security is the ability to prevent unauthorized access, misuse and forgery.

## Network Protocols and Communications(Part 1)

- Data communications are the exchange of data between two nodes via some form of link(transmission medium) such as a cable.
- Data flow means the data is going to flow from one node to another node. There are three different flows: Simplex(单工通信), Half Duplex(半双工通信), Full Duplex(全双工通信)
- Simplex:
  1. Communication is always unidirectional.
  1. One device can transmit and the other device will receive.
  1. Examples:Keyboards, Traditional monitors
- Half Duplex:
  1. Communication is both directions but not at the same time.
  1. If one device is sending, the other can only receive, and vice versa.
  1. Examples: Walkie-Talkies
- Full Duplex:
  1. Communication is both directions simultaneously(同时地)
  1. Device can send and receive at the same time.
  1. Example:Telephone line.
- All communication schemes will have the following things in common:
  1. Source and sender
  1. Destination and receiver
  1. Channel or media
- Protocol = Rule. It is a set of rules that govern data communication.
- Protocol determines:
  1. What is communicated?
  1. How it is communicated?
  1. When it is communicated?
- Elements of a protocol
  1. Message encoding: because we have two kinds of transmission medium(wired medium and wireless medium)
  1. Message formatting and encapsulation(封装): Encapsulate infomation to identify the sender and the receiver rightly.
  1. Message timing: Flow control and response timeout.
  1. Message size: Long messages must be broken into smaller pieces to travel across a network.
  1. Message delivery options: unicast(one destination), multicast(not all destinations), broadcast(all destinations)

## Network Protocols and Communications(Part 2)

- Message encoding: Protocols converts the data into signals or waves by appropriately identifying the device which it is connected to.
- Message formatting and encapsulation: With the data that it is going to send, this is going to add few more information with the data. That is the source IP address and the destination IP address.
- Message Timing: Flow control. It means if the receiver can handle ten data packets at a time, so that information will be sent to the sender. So the sender will start sending ten packets at a time. Response timeout. The sender must ensure that the data is received by the destination.
- Message Size: When we break the big box into small pieces, we will put numbers on every small box. So the destination can reassemble(重新组装) it in a right way. At the same time, this number will also help to identify if any packets or pieces are missing
- Peer-to-Peer Network
  1. No centralized administration.
  1. All peers are equal.
  1. Simple sharing applications.
  1. Not scalable.
- Client Server Network
  1. Centralized administration.
  1. Request-Response model.
  1. Scalable.
  1. Server maybe overloaded.

## Components of a Computer Network

- Nodes:
  1. End nodes(End devices): Computers, Network Printers, VoIP Phones, Telepresence endpoint, Security cameras, Mobile handled devices
  1. Intermediary nodes: Switches, Wireless Access Point, Routers, Security devices(Firewall), Bridges, Hubs, Repeaters, Cell Tower
- Media:
  1. Wired Medium(Guided Medium): Ethernet(以太网) straight-through cable, Ethernet crossover cable, Fiber Optic cable(光纤电缆) In fiber optic cable, the data is going to be carried in the form of light waves, light the fastest one in the world, so this is the fastest mode of wired communication. Coaxial cable(同轴电缆), USB cable
  1. Wireless Medium(Unguide Medium): Infrared(红外线): short range communication - TV remote control, Radio: Bluetooth, Wi-Fi, Microwaves: Cellular System(蜂窝系统) - Long communication, Satellite: Long range communication - GPS
- Services: e-mail, Storage services, File sharing, Instant Messaging, Online game, Voice over IP, video telephony, World Wide Web

## Classfications of Computer Networks

- Local Area Network(LAN)
  > A Local Area Network(LAN) is a computer network that interconnects computers within a limited area such as a residence, school, laboratary, university campus or office building.
  > LAN-DEVICES
  >
  > - WiredLAN(Example:Ethernet-Hub,Switch): Ethernet straight through cable connects devices of different kinds. If we want to connect this computer with that computer directly, then we have to go for ethernet crossover cable.
  > - WirelessLAN(Example:Wi-Fi)
- Metropolitan Area Network(MAN) /ˌmet.rəˈpɒl.ɪ.tən/ relating to a large city: A metropolian area network(MAN) is a computer network that interconnects users with computer resources in a geographic region of the size of a metropolitan area(City).
- Wide Area Network(WAN): A wide area network(WAN) is a telecommunications network that extends over a large geographical area for the primary purpose of computer networking. Internet is a wide WAN.
- New trends: Bring your own device. Online collaboration. Cloud computing: It is the on-demand availability of computer system resource, especially data storage and computing power, without direct active management by the user.(Google drive)

## Network Topology

- Arrangement of nodes of a computer network. Topology = Layout.
- Topology can be viewed as a physical topology and logical topology. Physical Topology —— Placement of various nodes. Logical Topology —— Deals with the data flow in the network.
- Bus Topology: All data transmitted between nodes in the network is transimitted over this common transmission medium and is able to be received by all nodes in the network simultaneously(= happening or being done at exactly the same time). A signal containing the address of the intended receiving machine travels from a source machine in both directions to all machines connected to the bus until it finds the intended recipient.
  ![](https://www.yellowwei.cn/img/2023-12-23.png)
  ![](https://www.yellowwei.cn/img/2023-12-23（1）.png)
- Ring Topology:

  1. A ring topology is a bus topology in a closed loop.
  1. Peer-to-Peer LAN topology.
  1. Two connections: one to each of its nearest neighbors.
  1. Unidirectional.
  1. Sending and receiving data takes place with the help of a TOKEN.

     ![](https://www.yellowwei.cn/img/2023-12-23（2）.png)
     ![](https://www.yellowwei.cn/img/2023-12-23（3）.png)

- Star Topology:

  1. Every node is connected to a central node called a hub or switch.
  1. Centralized Management.
  1. All traffic must pass through the hub or switch.

     ![](https://www.yellowwei.cn/img/2023-12-23（4）.png)
     ![](https://www.yellowwei.cn/img/2023-12-23（5）.png)

- Mesh Topology:

  1. Each node is directly connected to every other nodes in the network.
  1. Fault tolerant and reliable.

     ![](https://www.yellowwei.cn/img/2023-12-23（6）.png)
     ![](https://www.yellowwei.cn/img/2023-12-23（7）.png)

- Hybrid Topology:

  ![](https://www.yellowwei.cn/img/2023-12-23（8）.png)

## Basics of IP Addressing

- Every node in the computer network is identified with the help of IP address.
- There are two variations in IP address: IPV4 address and IPV6 address.
- IPV4:
  1. Logical address
  1. Can change based on the location of the device.
  1. Assigned by manually and dynamically.
  1. Represented in decimal and it has 4 octets(x.x.x.x).
  1. 0.0.0.0 to 255.255.255.255(32 bits).
- How to see IP address in real device? —— ipconfig

## Basics of MAC Addressing

- MAC stands for Media Access Control
- Every node in the LAN is identified with the help of MAC address.
- IP Address = Location of a person. MAC Address = Name of a person. IP addresses are router friendly addresses while MAC addresses are switch friendly addresses.
- MAC Address
  1. Physical address or Hardware address
  1. Unique, cannot be changed.
  1. Assigned by the manufacturer.
  1. Represented in hexadecimal(十六进制).
  1. Example: 70-20-84-00-ED-FC(48 bits).
  1. Separator: -.:
- IP address vs MAC address
  ![](https://www.yellowwei.cn/img/2023-12-23（9）.png)
- How to see MAC address in real device? —— ipconfig/all

## Basics of Port Addressing

- Reaching our city = Reaching our network.(IP address) Reaching our apartment = Reaching the host(MAC address) Reaching the right person = Reaching the right process.(Port Address)
- Port address or Port number
  1. In a node, many processes will be running.
  1. Data which are sent/received must reach the right process.
  1. Every process in a node is uniquely identified using port numbers.
  1. Port = Communication endpoint
  1. Fixed port and dynamic port numbers(0~65535) Example:Fixed port numbers: 25, 80 etc. OS assigned dynamic port numbers: 62424;

## Switching Techniques in Computer Networks

- Switching in computer network helps in deciding the best route for data transmission if there are multiple paths in a larger network.
- Circuit Switching(电路交换): Connection establishment——data transfer——connection disconnection
  1. A dedicated path is established between the sender and receiver.
  1. Before data transfer, connection will be established first.
  1. Example: Telephone network
- Message Switching(报文交换)
  1. Store and forward mechanism.
  1. Message is transferred as a complete unit and forwarded using store and forward mechanism at the intermediary node.
  1. Not suited for streaming media and real-time applications. Example: If sender is sending a real-time communication, two people are talking over voice and IP phones. So, we cannot expect intermediary node to collect all the data that is sent by the person and forward it. Because it is a real-time communication.
- Packet Switching(分组交换)
  1. The Internet is a packet switched network.
  1. Message is broken into individual chunks called as packets.
  1. Each packet is sent individually.
  1. Each packet will have source and destination IP address with sequence(顺序) number
  1. Sequence numbers will help the receiver to reorder the packets, detect missing packets and send acknowledgments. If the sender don't receive the acknowledgments in a period of time, it will retransmit that packet.
- Two Approaches to packet switching

  1. Datagram Approach

  ![](https://www.yellowwei.cn/img/2023-12-23（10）.png)

  1. Virtual Circuit Approach

  ![](https://www.yellowwei.cn/img/2023-12-23（11）.png)

## Layering in Computer Networks

- Layering means decomposing the problem into more manageable components.
- Advantages:
  1. It provides more modular design.
  1. Easy to troubleshoot.
- The protocols in each layer governs the activities of the data communication.
- Two layered architectures: The OSI Reference Model and The TCP/IP Model.
- The OSI Model
  ![](https://www.yellowwei.cn/img/2023-12-24.png)
- The purpose of the OSI model is to show how to facilitate communication between different systems without requiring changes to the logic of the underlying hardware and software.
- The OSI model was never fully implemented.
- The TCP/IP model
  ![](https://www.yellowwei.cn/img/2023-12-24（1）.png)
- Any communication to happen in computer network needs IP address, MAC address and port address. So each layer will take care of each of these addressing.

## The OSI Reference Model(Part 1)

- There are seven layers in the OSI reference model: Application Layer, Presentation Layer, Session Layer, Transport Layer, Network Layer, Data Link Layer and Physical Layer.(Please Do Not Throw Sausage Pizza Away)
  ![](https://www.yellowwei.cn/img/2023-12-24（2）.png)

## The OSI Reference Model(Part 2)

- Physical Layer converts the entire content into zeros and ones. It knows which kind of medium it is connected to. If it is connected to a wired medium, it converts entire zeros and ones into signals. If it is a Ethernet cable, it converts this into an electrical signal. If it is a fiber optic cable, it converts the entire bits of zeros and ones into light waves. In case, if it is a wireless medium, this entire group of zeros and ones are converted into waves.
- Application Layer:
  ![](https://www.yellowwei.cn/img/2023-12-24（3）.png)
- Presentation Layer:
  ![](https://www.yellowwei.cn/img/2023-12-24（6）.png)
- Session Layer:
  ![](https://www.yellowwei.cn/img/2023-12-24（5）.png)

## The OSI Reference Model(Part 3)

- Transport Layer:

  ![](https://www.yellowwei.cn/img/2023-12-24（7）.png)

- Network Layer:

  ![](https://www.yellowwei.cn/img/2023-12-24（8）.png)

- Data Link Layer:

  ![](https://www.yellowwei.cn/img/2023-12-24（9）.png)

- Physical Layer:

  ![](https://www.yellowwei.cn/img/2023-12-24（10）.png)

## The OSI Reference Model(Part 4)

- Recall services offered by each layer
  ![](https://www.yellowwei.cn/img/2023-12-25.png)
- Working of the OSI reference model

  1. The data is generated by the application layer.
  1. The source port number and destination port number are going to be added in the Transport layer.
  1. The source IP address and the destination IP address are going to added in the Network layer.
  1. In the Data link lyer, there are going to add header and trailer. Header contains source MAC address and destination MAC address and trailer deals with the error control related part.

     ![](https://www.yellowwei.cn/img/2023-12-25（1）.png)

## Addressing in Networking

- IP address and MAC address

![](https://www.yellowwei.cn/img/2023-12-25（2）.png)

- Any intermediary node will always process three layer information: Physical layer information, Data link layer information and Network layer information.
- It uses this computer's MAC address and next router's incoming interface as the destination MAC address.

## The TCP/IP Protocol Suite

- OSI reference model VS TCP/IP model

![](https://www.yellowwei.cn/img/2023-12-25（3）.png)

- The TCP/IP Model

![](https://www.yellowwei.cn/img/2023-12-25（4）.png)
![](https://www.yellowwei.cn/img/2023-12-25（5）.png)

- Protocol Data Unit(PDU): Protocol Data Units(PDUs) are named according to the protocols of the TCP/IP suite:data, segment, packet, frame and bits.
  1. Application Layer —— Data
  1. Transport Layer —— Segment
  1. Network Layer —— Packet
  1. Data Link Layer —— Frame
  1. Physical Layer —— Bits

## Basic Networking Commands

- ipconfig —— get the IP address of this computer
- ipconfig/all —— know the MAC address of this computer
- nslookup —— ask the DNS Server for IP address for the given server
- ping —— check whether two computers are reachable or not
- tracert —— trace the route how the packet from my computer is reaching the destination computer

## Hub(集线器)

- Hub works at the Physical layer of the OSI model.
- Used to set up LAN.
- Has multiple ports.
- Star topology.
- When a packet arrives at one port, it is copied to the other ports so that all segments of the LAN can see the packet.
- pros:
  1. Cheaper than switches.
  1. Works good for smaller network.
- cons:
  1. Issues with broadcast.
  1. No memory.
  1. Normally runs in half duplex mode.

## Switch(交换机)

- A switch is a networking hardware that connects devices on a computer network to establish a local area network.
- Unlike hub, switch has memory.
- Store MAC address table.
- Layer 2 Device for setting up LAN.
- Switch knows the destination MAC address connected to which interface. So it just forwards the data or the packet to only that interface.
- Hub VS Switch

  ![](https://www.yellowwei.cn/img/2023-12-26（1）.png)

## Router

- A router is a networking device that forwards data pakets between computer networks.
- A router is connected to at least two networks, commonly two LANs or WANs or LAN and its ISP's network.
- It is a layer 3(Network layer) device.
- Stores routing table.
- Switch VS Router

![](https://www.yellowwei.cn/img/2023-12-26（2）.png)

## Repeater(中继器)

- The data signals generally become too weak or corrupted if they tend travel a long distance.
- Repeater regenerates the signal over the same network.
- It operates at the Physical layer.
- They do not amplify(make the sound louder) the signal.
- It is a 2 port device.

![](https://www.yellowwei.cn/img/2023-12-26（3）.png)

## Bridge

- Bridge = Repeater + Functionality of reading MAC address
- It is a layer 2 device.
- It is used for interconnecting two LANs on the same protocol.
- It is also a two port device.
- Types of Bridges
  1. Transparent Bridges: These are the bridge in which the stations are completely unaware of the bridge's existance. Reconfiguration of the stations is unnecessary even if bridge is added or removed from network.
  1. Source Routing Bridges: In these bridges, routing operation is performed by source station and the frame specifies which route to follow.
- Router VS Bridge
  1. A bridge interconnects local area networks that are running on the same protocol and the bridge is a layer two device.It processes or it deals with the MAC address.
  1. A router interconnects two different local area networks that are running with two different protocols and router is a layer three device. It deals with IP address.

## List of various network devices

- Repeater, Hub, Switch, Bridge(two LANs on the same protocol), Router
- Multi-layer switch(Layer 3 Switch): Switch + Router
- Brouter: Bridge + Router
- Modem
- Firewall(Security Device)

## Fundamental Priciples of Physical Layer

![](https://www.yellowwei.cn/img/2023-12-26（4）.png)
