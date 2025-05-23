# Fawn

## Metadata

**tag**- #room/htb 
platform and room name - Hackthebox::Fawn
date = 2025-05-07
URL - [Hack The Box](https://app.hackthebox.com/starting-point)

---

## Questions

1. What does the 3-letter acronym FTP stand for?
```bash
File Transfer Protocol
```
2. Which port does the FTP service listen on usually?
```bash
21
```
3. FTP sends data in the clear, without any encryption. What acronym is used for a later protocol designed to provide similar functionality to FTP but securely, as an extension of the SSH protocol?
```bash
SFTP
```
4. What is the command we can use to send an ICMP echo request to test our connection to the target?
```bash
ping
```
5. From your scans, what version is FTP running on the target?
**Command:**
```bash
nmap -sV -vv $target -oN nmap 
```
**Answer:**
```bash
vsftpd 3.0.3
```
6. From your scans, what OS type is running on the target?
```bash
Unix
```
7. What is the command we need to run in order to display the 'ftp' client help menu?
```bash
ftp -?
```
8. What is username that is used over FTP when you want to log in without having an account?
```bash
anonymous
```
9. What is the response code we get for the FTP message 'Login successful'?
```bash
230
```
10. There are a couple of commands we can use to list the files and directories available on the FTP server. One is dir. What is the other that is a common way to list files on a Linux system.
```bash
ls
```
11. What is the command used to download the file we found on the FTP server?
```bash
get
```
12. Submit root flag
```bash
035db21c881520061c53e0536e44f815
```