# Network+ Notes
---

### [1.1 Understanding the OSI Model](https://www.youtube.com/watch?v=AYgXr1dynKU&list=PLG49S3nxzAnl_tQe3kvnmeMid0mjF8Le8&index=2)
---
- Open System Interconnection Reference Model
- There are unique protocols at every layer
- You will refer to this model for the rest of the career
- Layers
	- (1) **Physical Layer**
		- The **Physics** of the network (Signaling, Cabling, Connectors)
		- This layer isn't about protocols
		- "You have a physical layer problem" so fix your cabling, punch-downs, etc.
		- Example
			- Cables
			- fiber optic connections
			- the signal itself
	- (2) **Data Link Layer**
		- The basic network "language"
		- Data Link Control Protocols (MAC Address on Ethernet)
		- MAC Address refers to the hardware address of that particular adapter card
		- Any problem with a switch isn't able to address would refer to this layer
		- Example
			- Frame
			- MAC Address
			- Extended Unique Identifier
			- Switch
	- (3) **Network Layer**
		- The "routing" layer
		- Internet Protocol (IP)
		- Fragments frames to traverse different networks
		- Any problem with an IP Addresses, subnet masks, router isn't able to address would refer to this layer
		- Example
			- IP
			- Router
			- Packet
	- (4) **Transport Layer**
		- The "post office" layer
		- TCP (Transmission Control Protocol) and UDP (User Datagram Protocol)
		- Example
			- TCP Segment
			- UDP Daragram
	- (5) **Session Layer**
		- Communication management between devices
		- Control protocols, tunneling protocols
		- Example
			- Control Protocols
			- Tunneling Protocols
	- (6) **Presentation Layer**
		- Character encoding
		- Application encryption
		- Often combined with the application layer
		- Example
			- Application Encryption (SSL/TLS)
	- (7) **Application Layer**
		- The layer we see
		- HTTP, FTP, DNS, POP3
		- Example
			- Your eyes







