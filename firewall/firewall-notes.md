# Firewall Basics

## Introduction

A firewall is a security mechanism that monitors and controls incoming and outgoing network traffic according to predefined rules.

## Objectives

- Understand the purpose of firewalls
- Learn basic firewall concepts
- Understand firewall rules
- Learn INPUT, OUTPUT and FORWARD chains
- Practice basic iptables commands
- Understand ACCEPT, DROP and REJECT actions

## Important Concepts

### Source IP
The IP address of the system sending network traffic.

### Destination
The system receiving the traffic.

### Protocol
The communication protocol used, such as TCP, UDP or ICMP.

### Port
A logical endpoint used by network services.

### Actions

- ACCEPT – allows traffic
- DROP – silently blocks traffic
- REJECT – blocks traffic and sends a response

## iptables

iptables is a Linux command-line utility used to configure firewall rules.

### List Firewall Rules

```bash
sudo iptables -L -n -v
