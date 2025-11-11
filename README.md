# ARP-Attack-and-Network-Sniffing
# Explore Network Sniffing and ARP Attacks

# AIM:

To explore network sniffing and ARP Attacks

## STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode

### Step 2:

Investigate on the various categories of tools as follows:


### Step 3:
Open terminal and try execute some kali linux commands

## ARP Attacks:  
ARP spoofing: A hacker sends fake ARP packets that link an attacker's MAC address with an IP of a computer already on the LAN. 
Boot kali and Windows7 virtual machines.
In windows 7 give the command arp -a
## OUTPUT:
<img width="1484" height="734" alt="Screenshot 2025-10-29 085504" src="https://github.com/user-attachments/assets/3c472251-f407-448b-b552-97e0a962f8f2" />

From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:

<img width="1326" height="594" alt="Screenshot 2025-10-29 090409" src="https://github.com/user-attachments/assets/3a5cce88-cbfd-44a5-bf1c-4925b5a1f89c" />

 dsniff:


In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:

<img width="773" height="337" alt="Screenshot 2025-11-09 201329" src="https://github.com/user-attachments/assets/e4be97d0-7aa4-46e8-baba-64037b19eea3" />



In Kali issue the following commands:
sudo dsnifff
## OUTPUT:

<img width="676" height="219" alt="Screenshot 2025-11-10 152341" src="https://github.com/user-attachments/assets/c95b0f86-0079-433f-83d5-01caa7deff1a" />


Invoke the wireshark and examine the various menus  and controls of the tool:
<img width="1267" height="681" alt="Screenshot 2025-11-09 220713" src="https://github.com/user-attachments/assets/279def0d-fb49-44f6-95ed-68580a80fbac" />


## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
