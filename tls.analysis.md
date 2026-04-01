# TLS Handshake Analysis

## Objective
To analyze how secure connections are established using TLS (HTTPS).

## Method
Wireshark filter used:
tls.handshake

## Observations
- Client Hello packet was sent to initiate secure communication
- Server Hello packet responded with selected encryption parameters
- The server provided a digital certificate
- Encryption keys were exchanged

## Example
TLS handshake steps:
- Client Hello
- Server Hello
- Certificate
- Key Exchange

## Conclusion
TLS ensures secure communication by encrypting data between client and server.  
If TLS fails, HTTPS websites may show certificate errors or fail to load securely.
