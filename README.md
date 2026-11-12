# NETWORKWALKS-DAVIES-B084B-W2-PM1-Multiple-Kali-Tools
# Penetration Testing Report

## Footprinting & Network Scanning Phases

**W2-PM-FINAL | CYBERSECURITY | NETWORKWALKS**

---

## Report Information

| Field | Details |
|---|---|
| Pentester Name | Muhabwa Davies |
| Program/Batch | B084B-Networkwalks |
| Date | 12 November 2026 |
| Modules Completed | W2-PM1, W2-PM5 |
| Client/Target | Networkwalks and own local LAN |
| Permission Secured | Yes |
| Phases Covered | Phase 1 and Phase 2 |
| Remaining Phases | Phases 3–5 in progress |

---

## 1. Liability Disclaimer

I performed these activities only on systems and devices
where I had written authorization or which I personally own.
All activities were conducted for educational and research
purposes.

## 2. Introduction

This report covers footprinting of the networkwalks.com
domain using Kali Linux tools and network discovery
on my own local network using Zenmap.

The activities demonstrate two important stages of
cybersecurity assessment:

- Reconnaissance and footprinting
- Scanning and network discovery

## 3. Tools Used

| Tool | Purpose |
|---|---|
| Kali Linux | Operating system for reconnaissance |
| WHOIS | Domain registration information |
| WhatWeb | Website technology identification |
| Nslookup | DNS resolution |
| cURL | HTTP response header inspection |
| Wafw00f | WAF identification |
| DNSRecon | DNS record enumeration |
| Zenmap | Network discovery and visualization |
| Windows CMD | Local network configuration |

## 4. Activities Performed

### 4.1 Footprinting & Reconnaissance

I performed reconnaissance against the networkwalks.com domain using six Kali Linux tools: WHOIS, WhatWeb, Nslookup, Curl, Wafw00f and DNSRecon. Each tool was used to collect a different type of information about the target.

### 4.2 Network Scanning with Zenmap
For the second activity, I used Zenmap to perform network discovery on my local network. The practical required me to identify my local IP address and subnet, discover live hosts, identify their IP and MAC addresses, and generate a network topology.
I first used the Windows ipconfig command to identify my local IP address and LAN subnet. I then entered the subnet into Zenmap and selected Ping Scan to identify active hosts.
The example results provided in the practical identified four live hosts:
•	10.0.0.1
•	10.0.0.4
•	10.0.0.2

The example results also included three MAC addresses.
After completing the scan, I opened the Topology section in Zenmap, enabled the legend and saved the network topology in PDF format as required by the practical task.
Note: The actual subnet, number of hosts and addresses should be replaced with the results from my own network when submitting the report.


## 5. Evidence Collected



---

## Author

**MUHABWA Davies**

Cybersecurity Intern | B084B

**Program:** Networkwalks Cybersecurity Program  
**Week:** 02
