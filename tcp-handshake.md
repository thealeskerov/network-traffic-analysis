# TCP Handshake Analysis

## Objective
To analyze how a TCP connection is established between a client and a server.

## Method
Wireshark filter used:
tcp.flags.syn == 1

## Observations
- The client sent a SYN packet to start the connection
- The server replied with SYN-ACK
- The client completed the process with ACK
- This process is called the TCP three-way handshake

## Example
Handshake sequence:
- SYN
- SYN-ACK
- ACK

## Conclusion
TCP handshake is used to establish a reliable connection before data transfer begins.  
If SYN packets are sent but no SYN-ACK is received, the connection may be blocked by a firewall or the server may not be responding.
