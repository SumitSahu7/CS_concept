## Internet Protocols

## 1. What is TCP and Why It Is Widely Used

```
TCP (Transmission Control Protocol) is a reliable communication protocol.

It ensures that data reaches the destination completely, in order, and without errors.
TCP checks if packets are lost and resends them if needed.

Because of this reliability, TCP is used where accuracy is more important than speed.

- Interview tip: TCP guarantees delivery and order.
```

## 2. How TCP Connection Is Established (3-Way Handshake)

```
TCP establishes a connection before data transfer.

SYN – Client asks the server if it is ready.

SYN-ACK – Server agrees and acknowledges the request.

ACK – Client confirms and connection is established.

After this, data transfer starts.

- Interview tip: SYN → SYN-ACK → ACK.
```

## 3. What is UDP and Why It Is Used

```
UDP (User Datagram Protocol) is a fast but unreliable protocol.

It does not check whether data is received or not.
There is no retransmission or ordering of packets.

UDP is used when speed matters more than accuracy.

- Interview tip: UDP = fast, no guarantee.
```

## 4. How UDP Establishes Connection

```
UDP is connectionless.

The sender directly sends data to the receiver without handshaking.
There is no confirmation, no acknowledgment, and no connection setup.

This makes UDP very fast.

-Interview tip: UDP sends data without connection setup.
```

## 5. Difference Between TCP and UDP

```
Feature	      TCP	                         UDP
Connection	  Connection-oriented	         Connectionless
Reliability	  Guaranteed delivery	         No guarantee
Speed	      Slower	                     Faster
Ordering	  Maintains order	             No order
Use cases	  Web, email, file transfer	     Video streaming, gaming

- Interview tip: TCP = reliable, UDP = fast.
```
