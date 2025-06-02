# Elevate_Labs_05_Network_Traffic_Analysis
Packet capture and protocol filtering using Wireshark on Kali Linux.

# Task 5: Capture and Analyze Network Traffic Using Wireshark (Kali Linux)

## Objective
Capture live network packets on Kali Linux, generate traffic using `ping` and YouTube.com, and analyze at least 3 protocols using Wireshark.

## Tools Used
- Kali Linux
- Wireshark
- Terminal (for ping command)
- Firefox (for web traffic)
- Screenshot tool

## Deliverables
- `wireshark_capture.pcap` — Packet capture file
- `Network_Packet_Analysis_Report.txt` — Protocol analysis report
- `README.md` — This file
- `screenshots/` — Folder with step-by-step screenshots

## Summary of Steps
1. Start Wireshark with `sudo wireshark`
2. Capture traffic on active network interface (`wlan0` or `eth0`)
3. Run `ping google.com` to generate ICMP traffic
4. Visit `youtube.com` in Firefox to generate DNS, TCP, and HTTPS traffic
5. Apply protocol filters in Wireshark: `icmp`, `dns`, `tls`
6. Save capture as `.pcap`

## Screenshot List
- 1-wireshark-start.png
- 2-capture-started.png
- 3-ping-google.png
- 4-youtube-opened.png
- 5-capture-stopped.png
- 6-filter-icmp.png
- 7-filter-dns.png
- 8-filter-tls.png
- 9-save-capture.png

## Outcome
Hands-on experience in:
- Real-time packet capturing
- Protocol filtering and analysis (ICMP, DNS, TLS)
- Wireshark usage on Kali
