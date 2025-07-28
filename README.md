# RDP-Brute-Force-Attack-and-Remote-Login

This lab demonstrates using hydra to perform a brute force attack on a Windows 10 PC with the RDP protocol. Then from there initiating a successful login to the target system with the compromised login credentials using xfreerdp. This lab was performed in a segmented LAN environment for testing purposes. 


---


## 🖥️ **Live Project Webpage:**  
👉 [RDP Brute Force Attack and Remote Login](https://mark-thompson01.github.io/MTPortfolio/Lab%20Projects/RDP%20Brute%20Force%20Attack%20and%20Remote%20Login/)


---


## Lab Setup
The lab environment consists of two interconnected VMs:

> **Kali Linux VM:** Platform used to carry out and run a brute force login scan on the target using RDP via Hydra.
> **Windows 10 Desktop:** Target used to carry out the RDP brute force attack on.


---


## 🛠️ Tech Used
- Oracle VirtualBox
- Kali Linux VM
- Windows 10 Desktop
- nmap
- hydra
- xfreerdp


---



## 🔁 How to Recreate This Lab
- Download and install Oracle VirtualBox.
- Download, install, and setup a Kali Linux VM.
- Spin up a Windows 10 VM or use a Windows 10 lab segmented desktop.
- Use nmap to locate the Windows 10 machine on the network and identify port 3389 open.
- Specify a wordlist to be used (e.g., /usr/share/wordlists/rockyou.txt).
- Use Hydra in conjunction wuith the wordlist to run a brute force login scan.
- Use xfreerdp to login to the host with the login credentials found.

---


## What I've Learned
Through this project, I have learned how to:
- Use Nmap to locate a Windows host on the network and identify open port 3389.
- Use Hydra with a specified wordlist to run a brute force login scan on the target using the RDP protocol.
- Use xfreerdp to initiate a successful login attempt with cracked credentials.



---


## 📁 More from Me

Visit my full GitHub Pages portfolio to explore additional projects:

🔗 [MTPortfolio – Full Project Index](https://mark-thompson01.github.io/MTPortfolio/)



---



## 📜 License

This project is licensed under the 
[Creative Commons Attribution 4.0 International License (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/).

You are free to use, share, and adapt this content, with appropriate credit.
