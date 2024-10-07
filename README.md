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
Boot kali and Windows11 virtual machines.
In windows 11 give the command arp -a
### OUTPUT:
![322688678-a9ccbd51-db7d-4d35-810d-b29c5d6eda39](https://github.com/user-attachments/assets/5218b5ae-9237-4559-a48a-e42af777ac40)

From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>


### OUTPUT:
![322689145-8fcd5095-b08c-4dd9-8b40-5ec033bc9779](https://github.com/user-attachments/assets/f5428a96-049d-4387-aceb-3224c3b6e9fd)



###  dsniff:

In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
### OUTPUT:

![322689189-49bb7298-af00-4e43-8181-cd4000a27989](https://github.com/user-attachments/assets/fd63a127-adde-4377-8719-ea9feac5a12d)


In Kali issue the following commands:
sudo dsnifff
### OUTPUT:

![322689244-ec26f1b7-8a64-456a-bd07-332158a7fef1](https://github.com/user-attachments/assets/b98fe061-63b2-4485-8176-27b1f1a31809)


Invoke the wireshark and examine the various menus  and controls of the tool:

![322689307-b78ad25c-97f7-4e56-b01e-16b0854f94f1](https://github.com/user-attachments/assets/e3635181-81c2-4982-baf0-2c0600b8fdcc)


### RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully











