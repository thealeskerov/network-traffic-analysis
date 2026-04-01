# Packet Loss and TCP Analysis

## Objective
To analyze packet loss and understand TCP retransmissions and duplicate ACK behavior.

## Method
Wireshark filters used:
tcp.analysis.retransmission
tcp.analysis.duplicate_ack

## Observations
- Multiple TCP retransmissions were observed
- Duplicate ACK packets were detected
- Fast retransmissions occurred after duplicate ACK bursts

## Explanation
- Retransmission occurs when a packet is lost or not acknowledged
- Duplicate ACK indicates that the receiver is missing a packet
- TCP uses these mechanisms to ensure reliable delivery

## Possible Causes
- Unstable WiFi connection
- Network congestion
- Packet loss in the network path

## Conclusion
Packet loss affects network performance and causes retransmissions.  
Duplicate ACK and retransmissions are key indicators of network instability.
