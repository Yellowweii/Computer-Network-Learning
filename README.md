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
