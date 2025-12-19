# Task 5: Capture and Analyze Network Traffic Using Wireshark

## Objective
The objective of this task is to capture live network traffic using Wireshark and analyze different network protocols to understand how data is transmitted over a network.

## Tool Used
- Wireshark (Free Network Protocol Analyzer)

## Steps Performed
1. Installed Wireshark on a Windows system.
2. Opened Wireshark and selected the active Wi-Fi network interface.
3. Started live packet capture.
4. Generated network traffic by browsing websites and sending ping requests.
5. Stopped the packet capture after sufficient traffic was recorded.
6. Applied protocol-based filters to analyze different types of packets.
7. Identified multiple network protocols from the capture.
8. Saved the captured traffic as a `.pcap` file.
9. Took screenshots of important stages of the packet capture and analysis.

## Protocols Identified
### 1. DNS (Domain Name System)
DNS packets were observed during website access. These packets are responsible for resolving domain names into IP addresses before a connection is established.

### 2. TCP (Transmission Control Protocol)
TCP packets were identified showing reliable, connection-oriented communication. TCP ensures data delivery, error checking, and proper sequencing of packets.

### 3. UDP (User Datagram Protocol)
UDP packets were observed for lightweight and fast communication where reliability is not guaranteed. UDP is commonly used for DNS queries and real-time services.

## Observations
- Packet capture shows real-time communication between the system and external servers.
- DNS traffic appears whenever a website domain is accessed.
- TCP is widely used for web traffic due to its reliability.
- UDP provides faster communication but does not ensure packet delivery.
- Wireshark allows detailed inspection of packet headers and protocol behavior.

## Files Included
- `network_capture.pcap` – Captured network traffic file
- Screenshots showing:
  - Network interface selection
  - Live packet capture
  - Filtered DNS packets
  - Filtered TCP packets
  - Filtered UDP packets

## Conclusion
This task provided hands-on experience with network packet capturing and protocol analysis. Wireshark proved to be an effective tool for understanding how data flows across a network and how different protocols operate at various layers of communication.
