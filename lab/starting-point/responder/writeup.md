# <img src="https://labs.hackthebox.com/storage/avatars/0348ed41851064f497d155c2a6af359a.png" width="100" height="100" alt="Resource Logo"> [`responder`](https://app.hackthebox.com/starting-point)

`WinRM` `Custom Applications` `Protocols` `XAMPP` `SMB` `Responder` `PHP` `Reconnaissance` `Password Cracking` `Hash Capture` `Remote File Inclusion` `Remote Code Execution`


## About
- Type: `starting-point`
- Tags: `WinRM` `Custom Applications` `Protocols` `XAMPP` `SMB` `Responder` `PHP` `Reconnaissance` `Password Cracking` `Hash Capture` `Remote File Inclusion` `Remote Code Execution`
- Difficulty: `very_easy`
- Status: `in_progress` 
- OS: `windows`
- Authors: `HTB`
- Points: `0`

## Description


Description not provided



## Writeup


> To attack the target machine, you must be on the same network.
> Connect to the Starting Point VPN using one of the following options: Pwnbox or OpenVPN

```bash
export TARGET=""
```


> T1. When visiting the web service using the IP address, what is the domain that we are being redirected to?
> > **unika.htb**

> T2. Which scripting language is being used on the server to generate webpages?
> > **php**

> T3. What is the name of the URL parameter which is used to load different language versions of the webpage?
> > **ANSWER**

> T4. Which of the following values for the `page` parameter would be an example of exploiting a Local File Include (LFI) vulnerability: "french.html", "//10.10.14.6/somefile", "../../../../../../../../windows/system32/drivers/etc/hosts", "minikatz.exe"
> > **ANSWER**

> T5. Which of the following values for the `page` parameter would be an example of exploiting a Remote File Include (RFI) vulnerability: "french.html", "//10.10.14.6/somefile", "../../../../../../../../windows/system32/drivers/etc/hosts", "minikatz.exe"
> > **ANSWER**

> T6. What does NTLM stand for?
> > **ANSWER**

> T7. Which flag do we use in the Responder utility to specify the network interface?
> > **ANSWER**

> T8. There are several tools that take a NetNTLMv2 challenge/response and try millions of passwords to see if any of them generate the same response. One such tool is often referred to as `john`, but the full name is what?.
> > **ANSWER**

> T9. What is the password for the administrator user?
> > **ANSWER**

> T10. We will use a Windows service (i.e. running on the box) to remotely access the Responder machine using the password we recovered. What port TCP does it listen on?
> > **ANSWER**
