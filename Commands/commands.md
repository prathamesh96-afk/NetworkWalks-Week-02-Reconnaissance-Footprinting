# Commands Used – Week 02

This file contains the commands and tools used during the reconnaissance, footprinting and basic network configuration practical.

**Note:** Use these commands only on systems and domains you own or have permission to test.

## 1. Network Configuration Commands

### Display IP Address
```bash
ip addr
```
Displays the network interfaces and IP addresses of the Kali Linux machine.

### Display Routing Table
```bash
ip route
```
Displays the network routes and default gateway.

### Check DNS Server
```bash
cat /etc/resolv.conf
```
Displays the configured DNS resolver.

## 2. Network Connectivity

### Ping Command
```bash
ping -c 4 <target-ip-or-domain>
```
Checks basic network connectivity with the specified target.

## 3. Reconnaissance Commands

### WHOIS
```bash
whois <authorized-domain>
```
Retrieves publicly available domain registration information.

### cURL
```bash
curl -I https://<authorized-domain>
```
Retrieves HTTP response headers from the website.

### Nslookup
```bash
nslookup <authorized-domain>
```
Queries DNS records and resolves domain names.

### DNSRecon
```bash
dnsrecon -d <authorized-domain>
```
Performs DNS information gathering for the specified domain.

### Wafw00f
```bash
wafw00f https://<authorized-domain>
```
Checks whether a web application firewall (WAF) is detected.

### WhatWeb
```bash
whatweb https://<authorized-domain>
```
Identifies technologies used by a website.

## 4. Tools Used

- WHOIS
- cURL
- Nslookup
- DNSRecon
- Wafw00f
- WhatWeb
- Ping
- Kali Linux
- VirtualBox

## 5. Purpose

These commands were used to understand basic network configuration, connectivity testing, domain information gathering, DNS enumeration and website technology identification.

## 6. Network Scanning – Nmap

### Quick Scan
```bash
nmap -T4 -F 10.0.2.0/24
