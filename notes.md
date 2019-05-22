# E-commerce

<details>
<summary>
    Ecom policy and its impacts
</summary>

## E-commerce policy in India

Moderated by DIPP (Department of Industrial Policy and Promotion). 

### Changes in ecom policy in india & its impact on indian ecom

- Ecom marketplace will not keep any inventories

#### Positive impacts

#### Negative impacts


### Models

<!-- todo -->
Two prominent models used in ecom policy -

#### Inventory based Model
<!-- TODO -->
- Foreign Direct Investment (FDI) is not permitted.
- Example - 

#### Market Place Based Model

- No inventory or warehouse of its own
- internet facility for buyers and sellers
- Foreign Direct Investment (FDI) is permitted.
- Example - Alibaba
<!-- TODO -->

Amazon follows both models.

</details>

<details>
    <summary>
        Ecommerce, types, advantages, disadvantages, classification
    </summary>

## Ecommerce

Buying and selling of goods and services or exchanging info via network over internet.

Ecom is subset of E-business. 

### Types of Ecom

Two types of ecommerce -

- pure
- partial

Brick and Mortar

Click and Mortar

- online presence
- offline shops
- inventory present

Virtual Organisation

- no shops
- online services provided

### Benefits of Ecommerce

- windfall gain of new customers
    + worldwide audience
- Savings on operational cost
    + rent, infrastructure and other bills saved
- Data Driven Selling
    + recommendations
    + buying habits of customers
- Digital branding is fast and cost effective 
    + Traditional branding is expensive
    + Unproductive ads can be removed the very next day
- Digital sales pitching vs physical sales pitching
    + Less errors in digital
    + more detailed info in digital
- Remarketing and Retargeting
    + Easy to detect and target window shoppers
    + This is not possible in click and mortar
- 24x7 Potential real income
    + click and mortar available 24x7 unlike brick and mortar
- Profitable international scalability
- Fast order processing despite huge marketplace
    + Won't get crowded like brick and mortar

### Negative impacts of Ecommerce

- Dependent on website
- In brick and mortar, people can ask questions about the product and get instant replied
- Shipping delays
- Promotes amazon like mediators and not actual sellers

## Ecom classification

On the basis of nature of transaction -

B : Business, C : Customers, E : employees

- B2B
- B2C
- C2C
    + OLX
- C2B
    + Freelancers
- B2B2C
- B2E
- G2G
- G2C

</details>

<details>
<summary>
    Internet, Networking, communication layers, Network architecture
</summary>

## Internet and Networking

### General

- Web Server
- Web Client
- Browser
- Internet
- Web
    + web 1.0
    + web 2.0
    + web 2.2
    + web 3.0
- Protocol
- Cookies

### HTTP

- HTTP Uses TCP as transport layer protocol
- Stateless
- HTTP is an in-band protocol
    + Both commands and data go in same connection
- HTTP 1.0
    + Non persistant connection
- HTTP 1.1
    + longer duration connections
    + multiple files in single connection
- Diff between HTTP and HTTPS

### Reference Models (OSI / TCP)

- OSI ( Open systems Interconnection )
- TCP ( Transmission Control Protocol )
- Error control
- Flow control
- Access Control
    + todo
- encryption / decryption
- routing
    + flooding
- 7 Layers of OSI 
    + Application
    + Presentation
    + Session
    + Transport
    + Network - routing algo, etc
    + Data Link Layer - both h/w and s/w
    + Physical Layer - h/w
- In Band protocols
    + commands and data sent together
    + Example - HTTP, SMTP
- Out Band protocols
    + Commands and data sent separately
    + Example - FTP

Layers of OSI and their functions - 

#### Physical

- Phyical characteristics of the network
    + Types of cables
    + How long should the cable be
- Functional properties
    + Simplex / Half duplex / Duplex
- Topologies
    + Star, Bus
    + Ring, Mesh
    + Hybrid
- Encodings
    + Manchester 
    + Differential Manchester
- Devices at Physical Layer
    + Repeater
    + Network Interface Card
        * MAC Address aka physical address

#### Data Link Layer

- Flow control
    + Stop and Wait
    + Go back N (in practice)
    + Selective repeat
    + Difference b/w go back N and selective repeat
- Error Control
    + CRC (in practice)
    + Checksum
- Data framing
- Access Control
    + Carrier Sesning Multiple Access
    + Collison detection (CD) - suitable for wired
    + Collision Avoidance (CA) - suitable for wireless
    + Token Passing
    + Polling
- DLL has two parts
    + Media Access Control
        * Deals with  -
        * phyical addressing
        * framing
        * error control
    + Logical Link Control
        * todo
- Aloha, Slotted Aloha ?
- Framing
    + Frame structure
        * source address
        * destination address
        * data
- Circuit Switching
    + need physical connection between sender and receiver
    + dedicated connection
    + wastage of bandwidth
    + continous transmission of data
    + Only one sender possible
    + inefficient resource utilisation
- Packet Switching
    + many senders can simultaneously send to same receiver
    + better efficiency
    + better fault tolerance
        * If line is faulty, we have alternate routes
    + Virtual Circuit
    + Datagram approach

#### Network Layer

- host to host connectivity
    + Network layer
- end to end : process to process
    + transport layer
- hop to hop
    + Data link layer
- Logical Addressing
- Routing
- Fragmentation
- Physical address : MAC Address
    + Vendor ID
    + Date of Manufacturing
    + Serial number (48 bit)
- Logical address : IP address
    + Network ID
    + host ID

#### Transport later

- end to end : process to process
- Flow control
- error control
- segmentation
- Multiplexing and demultiplexing

#### Session Layer

- authentication
- authorization
- synchronization (checkpoints)
- dialog control (web conferencing)
 
#### Presentation Layer

- translation
- encryption / decryption
- data compression

### Internet addressing

#### Classful addressing

- IPv4
    + 32 bit
    + dotted decimal notation

- 5 classes
    + class name - prefix / identifier -  (identifier + network bits) + host bits
    + class A : 0 - (1 + 7) + 24
    + class B : 10 - (2 + 14) + 16
    + class C : 110 - (3 + 21) + 8
    + class D : 1110 - 4 + multicast addresses
    + class E : 1111 - 4 + research purposes
- In 8 bits hosts we have (256-2) available for hosts
    + 2 are reserved
    + `192.168.1.0` - network address
    + `192.168.1.255` - directed broadcast - all hosts in network
- Unicast
    + sender and receiver
- Broadcast
    + Limited (local broadcast) : within network
    + `255.255.255.255` - local broadcast
    + Directed broadcast : to other network
    
- Flooding 
    + destination - `0.0.0.0`

#### Subnetting

- dividing large networks into multiple smaller networks
- Subnet mask
    + ANDing of Subnet mask and IP address gives us Network ID
- `198.5.25.128/25`
    + subnet mask will be `255.255.255.128`

### Network Devices

- repeater
- Hub - phyical layer device
    + multiport repeater 
- Bridge
- Switch
- Router
- Gateway
    + Firewall 
    + Blocking
    + Network address translation
    + caching
    + Deep packet inspection
    + through all the layers

- Layer 3 firewall (network layer)
    + block a host - mac address checking
    + block a type of protocol
    + IP, SIP, DIP
    + prone to ICMP attacks ( echo packets )
    + prone to IP Address spoofing

- Layer 4 firewall (port access and blocking)
    + proxy
    + block peer to peer connectivity

### Network Architecture

How computers and connected and how tasks are allocated

- peer to peer
- client server architecture
    + 2 tier
        * client and server
    + 3 tier
        * Client, server and middleware
    + fat client (most of the work is done by client)
    + thin client (most work done at server, client is lightweight)
- MVC Architecture
    + model - database 
    + view - presentation
    + controller - app logic

</details>

<details>
    <summary>
        Distributed Systems
    </summary>

## Distributed Systems

Distributed System is a collection of independent computers, interconnected in a network that are capable if collaborating on a task.
eg - web searching

Such computers are called loosely coupled computers as opposed to tightly coupled computers.

Different forms of computing - 

- monolithic
    + multiple users can work with time sharing concept
- distrbuted
    + computers are independent have their own processors and resources
- parallel computing
    + more than one processor in a system and memory is shared.
- difference between parallel and distributed computing
- cooperative computing
    + SETI
    + Search for entra terrestial intelligence (Berkley University)
    + On internet, random computers do processing and send result back to main system.

#### Strengths of Distributed computing

- Advantages of cloud computers
    + affordability - cheaper than buying our own
    + availability - network access
- Resource sharing
- Scalability
- Increasing demand for resources can be addressed effectively with additional resources (data centers)
- Fault tolerance 
    + other system can replicate behaviour of the crashed system
    + so its functionality remain available

#### Weaknesses

- multiple point of failure
    + "a distributed system is one in which the failure of a computer you didnt even know existed can render your own computer unusable." - Leslie Lamport - turing award winner 2013
- security concerns
- Heterogenity of networks
    + two systems can have difference OS, hardware, network protocol
    + so we require a mechanism for bridging gap between networks
- Middleware
    + Software layer that provides a programming abstraction as well as masks the heterogenity of underlying OS, and programming languages.
    + RPC - remote process communication
    + Sockets

## Architectural elements of a Distributed System

4 key questions

### Q1. What are the entities that are communicating in a distributed system.

There are two prespectives - 

- system prespective
    + processes are communicating entities
    + threads, hosts
- programmers prespective
    + component based software engg (CBSE)
    + web services are communicating entities

#### System prespective

From a system prespective, the answer is very clear.
The entities are - typical processes leading to the prevailing view of a distributed system as processes coupled with appropriate IPC paradigms.
In some primitive environments, the underlying OS does not support process abstraction in that case communicating entities are nodes ( wireless sensors ).
In most distributed environments, the processes are supplemented by threads. In that case, threads are the endpoints of communication.

#### Programmers prespective

From a programmers prespective, entities are -

1. Objects : These have been introduced to enable and encourage the use of Object oriented approach in distributed system.
In distributed object based resources, a computation consists of a number of interacting objects representing the natural units of decomposition for the given problem domain.

2. Components - one part of a whole thing.
A component is an identifiable part of a larger program or construction. It provides a particular function or groups of related functions. In programming design, a system is divided into components that in turn are made of modules.

3. Webservices - webservices is a network accessible interface to application functionality built using standard internet technologies. It is an interface positioned between the application code and the user of the code. It acts as an abstraction layer separating the platform and the programming language specific details of how the application code is actually involved. Any language that supports the web services can access application functionality because of the abstraction provided by web services, it doe snot matter whether application services are written in JAVA and the browser written in C++ or the application service deployed on UNIX box while the browser is deployed on windows. Web services allow for cross platform inter-operability.

Object Oriented Programming vs Component Oriented Programming

- In the traditional object-oriented world, even though you may factor the business logic into many fine-grained classes, once those classes are compiled, the result is monolithic binary code. All the classes share the same physical deployment unit (typically an EXE), process, address space, security privileges, and so on. If multiple developers work on the same code base, they have to share source files. 
- In such an application, a change made to one class can trigger a massive re-linking of the entire application and necessitate retesting and redeployment of all the other classes.

- On the other hand, a component-oriented application comprises a collection of interacting binary application modules. An application implements and executes its required business logic by gluing together the functionality offered by the individual components. 
- Component-enabling technologies such as COM, J2EE, CORBA, and .NET provide the “plumbing” or infrastructure needed to connect binary components in a seamless manner, Because a component-based application is a collection of binary building blocks, you can treat its components like LEGO bricks, adding and removing them as you see fit. If you need to modify a component implementation, changes are contained to that component only.





### Q2. How do they communicate or more specifically what communication paradigm is used?

Three communication paradigms are used - 

1. IPC - inter process communication
2. Remote invocation
3. Indirect communication


Inter Process communication - 
It refers to the relatively low level support for communication between processes in the distributed system including message passing primitives, and socket programming. socket is a combination of IP address and port number.

Remote Invocation - 
It represents the most common communication paradigm in a distributed system covering a range of techniques based on a 2-way exchange between communicating entities in a distributed system and resulting in a calling of a remote operation procedure or a method. Various methods of Remote Invocation are -
1. Request Reply Protocol
2. Remote procedure call
3. Remote method invocation (JAVA RMI)

Indirect Communication - 
In this, the communication is through a 3rd entity allowing a degree of strong decoupling between sender and receiver. In particular, senders do not need to know who they are sending to (known as space uncoupling), and senders and receivers need not exist at the same time (time uncoupling)

Techniques - 
1. group communication
2. published and subscribe method (pub-sub method)

### Q3. what roles and responsibilities do they have in the overall architecture?

In a distributed system, processes (indeed objects, components, services) interact with each other to perform a useful activity.
In doing so, the processes take on given roles and these roles are fundamental in establishing the overall architecture of the distributed system.

The architectural style stemming from the role of individual processes are - 

1. Client server
2. Peer to peer

Client server - 
This is the architecture most often cited when distributed systems are discusses. In particular, client processes interact with individual server processes potentially separate host computers in order to access the shared resources. While the client server model offers a direct and relatively simple approach for sharing of data and resources, it scales poorly.

Peer to peer -
In this architecture all of the processes involved in task for activity play similar rules, interactively, cooperatively as peers without any distinction between client and server processes or the computer on which they run. In practical terms, all peers run the same program and offer the same set of interfaces to each other.
The key insight that led to the development of peer to peer is that the network and computing resources owned by a user of a service could also be put to use to support that service. p2p applications and Systems have enabled 10s and hundreds and thousands of computers to provide access to data and other resources that the collectively store and manage.

### Q4. how are they mapped onto the physical distributed infrastructure

The final issue to be considered is how entities such as objects or services map onto the underlying physical distributed infrastructure which will consist of a potentially large number of Machines interconnected by network of arbitrary complexity. 
the question of - where to place a given Client or server in terms of Machines and processes within the system is a matter of careful design. placement need to take into account the patterns of communication between entities, the reliability of given machine and their current loading, the quality of communication between different machines and so on.

Placement strategies - 

1. mapping of services to multiple servers
2. caching
3. mobile code
4. mobile agents


#### Mapping of services to multiple servers - 

Services may be implemented as several server processes in a separate host interacting to provide a service to the client processes. The server may - 

1. partition the set of objects on which the service is based and distribute those objects between themselves. eg - web server
2. Maintaining replicated copies of them on several hosts.

example - Sun Network Information Services (NIS)

It enables all the computers in a LAN to access the same user authentication data when user login. Each NIS server has its own replica of a common password file containing list of users, login names and encrypted passwords. 

#### Caching

A cache is the store of recent user data objects that is closer to one Client or a particular set of clients than the objects themselves. 
when a new object is received from server, it is added to the local cache store replacing some of the existing objects if necessary. 

for example - web browsers maintain a cache of recently visited pages and other resources in the clients local file system. 

for example -  Web Proxy server implemented by gateway. 
It provides a shared cache of web resources for the client machines at a site or across several sites. the purpose of proxy server is -

1. to keep machines behind it anonymous for security purposes. they may be used to access remote web server through a Firewall.
2. To increase availability and performance of the service by reducing the load on a WAN and web server.

#### Mobile Code

Applets are a well known and widely used example of mobile code.
code is downloaded on browser and run locally to given faster interaction time as no network latency. It is however, a potential security threat to the local resources in the destination. Therefore, browsers give applets limited access to local resources.

Java was designed carefully to support sandboxing model. 
JVM was designed with mobile code in view. Browser often limit applet access to sockets, and file system. JVM provides further two measures - 

1. The downloaded classes are stored separately from the local classes, preventing them from replacing classes with spurious version.
2. The bytecodes are checked for validity. 

#### Mobile Agents

Mobile agent is a running program (including both code and data) that travels from one computer to another in a network carrying out the task on someone's behalf such as collecting information and eventually returning results.
It is a type of software agent with the feature of autonomy, Social ability, learning and most importantly mobility.
mobile agents might be used to install and maintain a software of the computer within an organisation or to compare the prices of products from a number of medals by visiting each vendor site and performing a series of database operations.
mobile agents like mobile code are a potential security threat to the resources of the computer they visit. The environment receiving mobile agent should decide which of the local resources of the user should be allowed to use, based on the identity of the user on whose behalf the agent is acting.

There are many reasons to start using mobile agents - 

1. reduced network load - because computation is moved to the data storage location, instead of moving data to server. Thus reducing network load.
2. Overcome network latency - in real time systems
3. Fault tolerance - mobile agents react dynamically and autonomously to the changes in the environment which makes them robust and fault tolerant. they have the ability to distribute themselves in a network in such a way as to maintain the optimal configuration for solving the particular problem. If a host is being shutdown all its executing agents will be warned and given time to dispatch to another host to continue their task.
4. Asynchronous and autonomous execution - Mobile agents operate asynchronously. once a mobile agent is dispatched from the home machine it can disconnect from the network. the mobile agent executes autonomously without the intervention of the home machine machine can reconnect at a later time collect the agent.

Working of Mobile Agents -

- home machine
- code and state
- one machine to another until task is done
- back to home machine

Properties of Mobile Agents -

- Adaptive learning
- autonomy
- mobility

Applications of mobile agents -

- Parallel computing
- data collection (and processing on client)
- e-commerce - Mobile agent can travel to different trading sites that help to locate the most appropriate deal, negotiate the deal and your finalize business transactions on behalf of their owners. a mobile agent can be programmed to bid in an online auction on behalf of the user, the user himself need not be online during the option.

Disadvantages - 

- the main drawback is the security risk involved using mobile agents
- security risk is two fold
    + A malicious MA can damage a host
    + A malicious host can tamper with the functioning of a mobile agent.


</details>


<details>
    <summary>
        IPC and marshalling
    </summary>

## IPC

IPC - heterogeneous hosts.

Little and Big endian formats. 3 ways to deal with them - 

1. prior to issuing a `send`, p1 can convert the vale of the integer to little endian for p2.
2. p1 sends as it is, p2 upon receiving converts to little endian.
3. the exchange format is decided. data sent will always be converted to this format and upon receiving converted to native representation.

#### Marshalling

An agreed standard for the representation of data structures and primitive values is called `marshalling`. It is a process of taking a collection of data items and assembling them into a form suitable for transmission in a message.

Marshalling can be used for -

1. right to disk
2. for sending the data to other platforms over the network.

Data Marshalling is needed for all IPC and includes necessary steps for conditioning the data to be transmitted. They are -

1. Serialize the data structure
2. Converting data values to external representations.


</details>

<details>
    <summary>Security & cryptography</summary>

- entity authentication
    + password
    + OTP
    + Biometric
- Message authentication
    + Checksum
    + CRC
- symmetric keys
- cryptographic dilemma


### Escrow

Financial management where 3rd party regulates payments of funds required for two parties involved in a given transaction.

Basically, A 3rd party trusted by both seller and buyer to help with payment.

RERA (real estate and development)

Escrow services used in -
- public / private project
- Website development

</details>

<details>
    <summary>
        Payment methods
    </summary>

- RTGS (real time gross settlement)
    + Real time
    + min amount 2 lakhs, max no bound
    + TAX - 2.5% + GST to 5% + GST
- NEFT
    + settled in batches
    + no limits
    + TAX - 2.5% + GST

- How credit card transaction processing works ?
- How payment gateway works

</details>
