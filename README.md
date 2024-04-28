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
![image](https://github.com/Hariharan-061102/ARP-Attack-and-Network-Sniffing/assets/93427270/2060e337-cb22-4986-b97f-ebcdbc63b539)


From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:
![image](https://github.com/Hariharan-061102/ARP-Attack-and-Network-Sniffing/assets/93427270/b681f783-261c-4597-9f3c-e714794ed317)


 dsniff:
In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:
![image](https://github.com/Hariharan-061102/ARP-Attack-and-Network-Sniffing/assets/93427270/a5e262c0-44e1-4372-84d4-a9f38c26a399)


In Kali issue the following commands:
sudo dsnifff
## OUTPUT:
![image](https://github.com/Hariharan-061102/ARP-Attack-and-Network-Sniffing/assets/93427270/9eaf5f48-02a7-4f3a-8a51-46920e78ae9d)



Invoke the wireshark and examine the various menus  and controls of the tool:

![image](https://github.com/Hariharan-061102/ARP-Attack-and-Network-Sniffing/assets/93427270/4531bc11-5edd-4e60-8b68-1db8ff5abfcf)


## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
