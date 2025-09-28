WORK IN PROGRESS 
# Summary

Best way to learn things in IT is to get hands-on experience, whether it's professional experience or none professional, it's the effort and the passion that matters. As an upcoming Cybersecurity professional. I want to get better and more familiar with different OSes and how they behave and some tools such as Wazuh. Big aspect of Cybersecurity is the systems we run, such as RHEL and Windows Server. I have an upcoming project about Windows Server, this project focuses only on Linux. 

# Setup

- Unfortunately, my budget for hardware is very tight but I still want to learn and make most out of my Proxmox server. 

**Laptop Specs:**
- **CPU:** Intel Core i5-8250U
- **GPU:** Intel UHD Graphics 620 (Integrated)
- **Memory:** 8GB
- **Disk:** 210GB
- **Network**: Single Device 

**Servers:**
- Arch Server
- Linux Server (Ubuntu Server)
- Wazuh Server (an EDR Server)
- RockyRHCSA (Rocky Linux, I called it RHCSA because I wanted to practice for my RHCSA exam using Rocky)
- FedoraRHCSA (Same deal as Rocky Linux, Fedora to practice my RHCSA Exam) 
- Alpine Server (Runs Containers)
  
**Note:** I only run one or two servers at a time, otherwise my system will crash. 

**System Structure Diagram**:

<img width="711" height="922" alt="image" src="https://github.com/user-attachments/assets/f9683b2f-08c7-4751-bc42-9bf4f5efb6e1" />




**Screenshots:**

<img width="244" height="249" alt="image" src="https://github.com/user-attachments/assets/60c5630a-eafc-45cf-83b1-72e4ea21efd1" />

<img width="747" height="236" alt="image" src="https://github.com/user-attachments/assets/a87665bd-5a4e-495d-860e-b5aef6021e83" />



# Whats in my Arch Server? 

I run Arch Linux on my main PC desktop. We all know Arch is known to break every now and then, sometimes it takes one command. Awhile the solution to that is backups and/or rollbacks, however that takes some space on a hard drive. So therefore, 

**The Purpose:** 
- Headless (Lightweight)
- Learn, write and run scripts  
- Running as a test environment for updates, packages, software, anything that may break my main PC Desktop. 
- Rely on CLI

**Screenshots:**

<img width="515" height="326" alt="image" src="https://github.com/user-attachments/assets/7ec991a3-f544-4eec-92b7-500ea9f9dba2" />

Update and a tiny simple script for testing:

<img width="301" height="76" alt="image" src="https://github.com/user-attachments/assets/2cbadba7-6975-406c-95f4-076425dc5924" />

<img width="368" height="61" alt="image" src="https://github.com/user-attachments/assets/2276260e-062f-4571-8f63-48e4044c04df" />


# Whats in my Linux Server (Ubuntu Server)? 
It's running a basic FTP server, mostly for learning and managing, there's couple of images and videos just to test it but again it being on a very low performance laptop, I'm limited to practical use. So therefore,

**The Purpose:** 
- FTP Server
- Managing Users
- Maintaining it as if it was an enterprise server 
- Testing Environment 
- Some scripting 

**Screenshots:**

<img width="526" height="337" alt="image" src="https://github.com/user-attachments/assets/20c83027-5480-45b4-b6b1-f7512a183250" />



<img width="362" height="405" alt="image" src="https://github.com/user-attachments/assets/2307ba75-7b3f-4c30-8b6f-afe2d0f9c5c9" />



<img width="639" height="429" alt="image" src="https://github.com/user-attachments/assets/0cdde43e-49b6-4c77-a30f-466ce5c76e10" />


# Whats in my Wazuh Server (Ubuntu)? 
I enjoy learning and getting better at IPS, IDS, SIEM, EDR softwares, tools and solutions. One of my go to SIEM (mostly because it's free) is Wazuh. Wazuh provides a comprehensive dashboard of the system in question. My favorite aspect of Wazuh is "Threat Hunting" which uses logs and visuals to detect any suspicious behavior. We're gonna do a simple test using Kali Linux, attacking the Linux Server. 


**The Purpose:** 
- IPS/IDS
- Incident Response
- Monitoring any anomaly actives 
-  A cool looking dashboard 
- Testing it's detection using Kali (On a different system then Proxmox)

**Screenshots:**

**Kali:**
<img width="343" height="22" alt="image" src="https://github.com/user-attachments/assets/c9b4654f-fe1a-4634-a3fd-a061c3026333" />

**Note:** This is ethical hacking and the system I tested it on was my own Proxmox machine, which I have full access and permission too.

**Linux Server:** 

<img width="1062" height="105" alt="image" src="https://github.com/user-attachments/assets/998b4945-1039-4a51-b0e2-e0f06e6e4a6a" />


# Whats in my Rocky Server & Fedora Server? 

My system cannot run RHEL, it doesn't have the required specs that RHEL 10 needs. So, I did the next best thing which was install Rocky Linux. It's good to get familiar with other RHEL like systems, such as Fedora. Awhile Rocky and Fedora feels like one to one copy, there were some different tiny aspects of the two disros. For example, Fedora default environment is GNOME and Rocky default is a different flavor of GNOME. So therefore,  

**The Purpose:** 
- Break the system and push it to it's limits for learning experience 
- Learn it's environment for RHCSA 
- Learn, write and run scripts  


**Screenshots:**




**Screenshots:**


# Whats in my Alpine Server? 

I've never heard of or used Alpine before, it turns out it's a great lightweight distro for containers. Awhile Proxmox has a specialized container aspect of it, I'm not very familiar with it. I've ran containers multiple times before on Ubuntu Server, using CLI and Portainer. 

**The Purpose:** 
- Run Docker
- Deploying container images 
- Runs portainer 





**Screenshots:**

