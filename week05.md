# Week 05

## task 02
![ethernet](./image/week05_task01_ethernet.png)

Below is a quick summary of each trail:

255.255.255.255/32: IPv4 Limited Broadcast — Network-wide broadcast traffic is sent to all hosts on the local physical segment.

224.0.0.0/4: IPv4 Multicast Range — Directs traffic sent to multicast groups (224.0.0.0–239.255.255.255).

10.178.35.255/32: Subnet Broadcast — Broadcast address specific to the local 10.178.32.0/22 subnet.

Local IPv4 Address — Represents the IP address that this local computer has been assigned.

10.178.32.0/22: Local Subnet Route — Directs traffic to local neighbor devices (10.178.32.1–10.178.35.254) without needing a router.

0.0.0.0/0: Default Gateway — Routes all Internet and external network traffic through gateway router 10.178.32.1.

ff00::/8: IPv6 Multicast Block – All IPv6 group traffic on the local interface.

fe80::91fd:c26c:d9b6:80b: Local IPv6 Address — IPv6 Address assigned to this machine that is used for local communication.

fe80::/64: IPv6 Link-Local Subnet — IPv6 traffic— a reserved address that links together devices that are directly connected on the same physical link.
 IPv6 Link-Local Subnet: IPv6 traffic is sent to other devices that are attached to the same physical link.
