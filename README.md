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
<img width="669" height="289" alt="image" src="https://github.com/user-attachments/assets/00cb78a4-4ddb-4679-a5b8-906cc61cf90a" />



From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:

<img width="945" height="262" alt="image" src="https://github.com/user-attachments/assets/70a74a63-b3da-4d81-886b-a32881ad10d6" />


In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org

<img width="720" height="80" alt="image" src="https://github.com/user-attachments/assets/7b002c4a-acce-494d-82de-b80e8bd7b8e1" />


 dsniff:

## OUTPUT:




In Kali issue the following commands:
sudo dsnifff
## OUTPUT:



Invoke the wireshark and examine the various menus  and controls of the tool:


## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
