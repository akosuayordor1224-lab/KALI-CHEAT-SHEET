# My Kali Linux Cheat Sheet
### By Yordor Diana Mary | NetworkWalks Academy - Cybersecurity Intern

These are the commands I used in Week 2 for Footprinting and Scanning. All tested by me in Kali Linux.

## 1. WHOIS - Find who owns a domain
whois networkwalks.com

## 2. WhatWeb - Find what technology a website uses
whatweb https://networkwalks.com

## 3. Nslookup - Find IP address of a website
nslookup networkwalks.com

## 4. Curl - Check website headers
curl -I https://networkwalks.com

## 5. Wafw00f - Check if website has a firewall / WAF
wafw00f https://networkwalks.com

## 6. DNSRecon - Find DNS records
dnsrecon -d networkwalks.com

## 7. Nmap / Zenmap - Scan a network (I scanned my own Kali: 127.0.0.1)
nmap -T4 -A -v 127.0.0.1

---
Note: I only test on networkwalks.com (with permission) and my own machine 127.0.0.1. Never test on websites without permission.
