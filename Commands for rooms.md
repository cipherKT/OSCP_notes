# Commands for rooms

## Metadata

**tag**- #room
date = 2025-05-07

---

## Initial commands 
1. export IP as env variable 
```bash
export target=10.129.161.243 # Change the IP 
```
## Nmap 

This is for scanning all the open ports of machine

```bash
nmap -sV -vv $target -oN nmap 
```
- A basic scan that scans for all open ports 
```bash
nmap -A -T4 -p23 -vv $target -oN nmap_aggressive
```
- Aggressive command for scanning specific port 
