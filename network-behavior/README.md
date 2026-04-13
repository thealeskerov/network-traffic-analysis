# Network Behavior Analysis

## Overview
This lab demonstrates real-world network behavior using basic tools.

---

## TTL (Time To Live)

Command:
ping -i 1 google.com

Observation:
TTL expired in transit.

Explanation:
Each router decreases TTL by 1.
When TTL reaches 0, the packet is dropped.

Default TTL:
- Windows: 128
- Linux: 64

---

## Traceroute

Command:
tracert google.com

Observation:
- Multiple hops (routers)
- Some hops timed out

Explanation:
Each hop represents a router in the network path.

---

## VPN

Steps:
1. Run tracert without VPN
2. Enable VPN
3. Run tracert again

Observation:
- Route changed
- Different IP addresses

Explanation:
Traffic is routed through VPN tunnel instead of direct internet path.

---

## QoS

Observation:
Video streaming remained stable during file download.

Explanation:
QoS prioritizes important traffic such as video and voice.
