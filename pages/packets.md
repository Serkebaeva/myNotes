aliases:: web, http, url

- **Packets explained**
	- When data is sent across the web, it is sent in multiple small chunks called packets.
		- A [[header]], which includes details such as the server and client [[IP]] address, the packet number, the total number of packets in the transmission, and details of the protocols used in the transmission.
		- A [[payload]], which contains the actual data sent in the packet.
		- There are multiple reasons why data is sent in small packets, but most significantly:
			- They are sometimes dropped or corrupted, and when this happens, it's quicker and easier for the client to request the missing packets rather than an entire file.
			- The packets can be routed along different paths, making the transmission as efficient as possible and reducing the possibility of slowing down the network - especially when many users are requesting the same resource simultaneously. The packets may arrive out of sequence, but the client can use the information in the packet headers to make sure they are assembled in the correct order.
- https://developer.mozilla.org/en-US/docs/Glossary/Packet