# Wireshark Network Traffic Analysis

## 1. Objective

The objective of this activity was to capture and analyze network traffic using Wireshark in an authorized virtual laboratory environment.

## 2. Lab Environment

- Client: Kali Linux
- Client IP: 192.168.128.4
- Target: Metasploitable2
- Target IP: 192.168.128.3
- Network Interface: eth1
- Tool: Wireshark

## 3. Protocols Analyzed

The following protocols were captured and analyzed:

- ICMP
- TCP
- UDP
- DNS
- HTTP
- FTP

## 4. ICMP Analysis

ICMP traffic was generated using:

```bash
ping -c 4 192.168.128.3
icmp
The capture showed ICMP Echo Request packets sent from Kali to Metasploitable2 and ICMP Echo Reply packets returned by the target.
