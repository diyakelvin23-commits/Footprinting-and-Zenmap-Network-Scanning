# Footprinting and Zenmap Network Scanning

## Project Overview
This project documents practical cybersecurity activities focused on footprinting, reconnaissance, and network scanning using Kali Linux tools and Zenmap.

## Objectives
- Understand the footprinting and reconnaissance process.
- Gather publicly available information about a domain.
- Identify technologies and services associated with a target website.
- Perform a network discovery scan using Zenmap.
- Document findings and recommend basic security improvements.

## Tools Used
- Kali Linux
- WHOIS
- WhatWeb
- Nslookup
- cURL
- Wafw00f
- DNSRecon
- Zenmap (Nmap)

## Methodology

### 1. Footprinting
Various reconnaissance tools were used to collect publicly available information about the target domain, including:
- Domain registration information
- DNS records and IP address information
- Web server and technology details
- HTTP response headers
- Web application firewall information

### 2. Network Scanning with Zenmap
Zenmap was used to perform a ping scan of a local `/24` network to identify active hosts.

The scan identified **two responding hosts**. A network topology diagram was also generated to illustrate the discovered devices.

Specific local IP addresses and MAC addresses have been withheld from this public repository for privacy.

## Key Findings
- Public DNS and domain registration information was collected.
- Web technologies and server information were identified.
- Two active hosts were detected during the local network scan.
- A network topology diagram was generated.

## Security and Authorization
Network scanning should only be performed on systems and networks that you own or have explicit permission to assess.

Private network identifiers and personal information have been excluded from this public report.

## Project Report
See the PDF report in this repository:

**Footprinting_and_Zenmap_Public_Report.pdf**

## Conclusion
This project provided practical experience with information gathering, footprinting, DNS enumeration, web technology identification, and network discovery using common cybersecurity tools.
