# Packet Sniffer for Network Traffic Monitoring

## Overview
This project aims to develop a **packet sniffer** for capturing and monitoring network traffic in real-time. The tool provides detailed insights into each network packet, helping users understand web traffic and identify data flow anomalies. 

### Key Features:
- **Source and Destination IP Addresses**  
- **Ports and Protocols**: TCP, UDP  
- **Data Size**  
- **HTTP Request Analysis**: Request types (GET, POST) and associated URLs  

By gaining visibility into network traffic, this tool assists in detecting unusual activities and enhances understanding of data flow.

---

## Features
1. **Real-Time Packet Capture**  
   - Continuously monitor live network traffic as it happens.

2. **Detailed Packet Information**  
   - Display crucial details such as:
     - Source IP and Destination IP
     - Ports
     - Protocols (TCP, UDP)
     - Data Size

3. **HTTP Analysis**  
   - Identify and display HTTP request types (e.g., GET, POST) and their URLs.

4. **Traffic Filtering**  
   - Filter captured traffic based on:
     - Protocols (e.g., TCP, HTTP)
     - Specific IP addresses for focused analysis.

---

## Objectives
- **Capture and Display Network Packets in Real-Time**  
  Gain live visibility of network traffic.

- **Detailed Packet Breakdown**  
  Present in-depth information about each packet.

- **Filtering Capabilities**  
  Enable targeted analysis by filtering traffic based on criteria.

- **HTTP Request Identification**  
  Provide insights into web traffic through HTTP request details.

---

## Expected Outcomes
- A fully functional tool for real-time **network traffic monitoring**.  
- Ability to **filter and analyze specific packets**, including HTTP requests.  
- Enhanced visibility to detect **anomalies in network data flow**.  

---

## How to Run the Tool
1. Install the required dependencies (e.g., `scapy`, `tshark`, or `pyshark` for Python).  
2. Run the script with administrative privileges for packet capture.  
3. Use the tool's interface or console commands to filter and monitor traffic.

---

## Future Enhancements
- Add support for saving captured packets to a file (e.g., PCAP format).  
- Enhance filtering capabilities with custom query support.  
- Integrate visualization tools for traffic patterns.

---
