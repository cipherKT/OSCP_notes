# Meow

## Metadata

**tag**- #room/htb
platform and room name - Hackthebox::meow
date = 2025-05-07 
URL - [Hack The Box](https://app.hackthebox.com/starting-point)

---

## IP: 10.129.161.243
## Questions

1. What does the VM Acronym stand for?
```
Virtual Machine
```
2. What tool do we use to interact with the operating system in order to issue commands via the command line, such as the one to start our VPN connection? It's also known as a console or shell. 

```
terminal
```

3. What service do we use to form our VPN connection into HTB labs? 
```
Openvpn
```
4. What tool do we use to test our connection to the target with an ICMP echo request? 
```
ping
```
5. What is the name of the most common tool for finding open ports on a target? 
```
nmap
```
6. What service do we identify on port 23/tcp during our scans?

**command:**
```bash
nmap -sV -vv $target -oN nmap 
```
![[Pasted image 20250507231706.png]]

**Answer:**
```
telnet
```
7. What username is able to login into target over telnet with a blank password?
**Command:**
```bash
nmap -A -T4 -p23 -vv $target -oN nmap_aggressive
```

**Answer:**
```
root
```
8. Submit root flag
```
b40abdfe23665f766f9c61ecba8a4c19
```