# OSI Model
### Definition
- A standard model defined by ISO that divides the networking process into 7steps.

### Why OSI Model created
- It is because of the fact that it will be easy for troubleshooting the network problems. 
- Only the layer in which the problem exists will be modified. Other layers can be left untouched.

### Structure
#### 1. Physical Layer
- Definition: This layer converts data into electrical signals(Bit).
- Role:
  - Only proceeds with transmitting data and only in charge of converting data into electrical signals.
  - Doesn't mind the content of the data and errors they have.
- PDU(Protocol Data Unit): Bit
- Example: Hubs, Repeaters

#### 2. Data link Layer
- Definition: This layer manages the flow of communications so that the data can be transmitted securely.
- Role:
  - Ensures reliable transportation point to point.
  - Gives the frame a MAC address which is physically assigned.
  - Transmits data from Physical layer with MAC address through Bridge or Switch.
  - Performs Error control, Retransmission, and Flow control.
  - These features provide for transmitting data, finding and editing errors that can occur in the Physical layer.
- PDU: Frame
- Example: Ethernet, Switch, Bridge

#### 3. Network Layer
This layer transmits data fast and securely to the destination. Select a route through the router and IP address, and forward packets according to the route.
- PDU: Packet
- Example: IP, ICMP, IPSec

#### 4. Transport Layer
This layer activates communication through TCP and UDP protocols. It keeps the port open and provides programs for transmission.
- PDU: Segment
- Example: TCP, UDP
  - TCP: Reliable, connection-oriented
  - UDP: Unreliable, disconnected and real-time

#### 5. Session Layer
This layer is responsible for the logical connection and for creating and eliminating TCP/IP sessions. 
- Ex: API, Socket

#### 6. Presentation Layer
This layer determines the way of transmitting data. This layer is in charge of providing independence and encrypting data.
- Data conversion(데이터 변환), Compression(압축), Encryption(암호화)
- Ex: JPEG, GIF

#### 7. Application Layer
This layer is the end-user layer that performs general application services.
- Ex: HTTP, FTP
