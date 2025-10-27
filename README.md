# 🧠 Wireshark Network Traffic Analysis
# 📋 Project Overview

This project demonstrates basic network traffic analysis using Wireshark.
The goal was to capture, filter, and analyze packets generated during normal web activity to identify key network protocols and understand their roles in communication.

# ⚙️ Steps Performed

1.Installed Wireshark on Kali Linux.

2.Started packet capture on the active network interface.

3.Generated traffic by:

-Browsing the website: https://elevatelabs.in

-Pinging the same domain using the terminal (ping elevatelabs.in)

4.Captured packets for about one minute.

5.Filtered packets in Wireshark by:

•http — for web traffic

•dns — for domain resolution

•tcp — for transport-level communication

6.Identified at least three protocols in the captured data:

•DNS – Used for domain name resolution.

•TCP – Ensured reliable transport of data.

•HTTP – Managed web content exchange between client and server.

7.Exported the capture as a .pcap file for documentation and analysis.
