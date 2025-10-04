NAME: GOPIKA A

REG NO: 212224100017

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

<img width="685" height="506" alt="Screenshot 2025-09-20 173027" src="https://github.com/user-attachments/assets/3fae9506-81e4-42e1-a4c2-29f507775a70" />

From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:

In Kali issue the following commands: sudo dsnifff

## OUTPUT
<img width="451" height="143" alt="image" src="https://github.com/user-attachments/assets/bc804e59-f478-48b8-ae38-670113f3bfbb" />


Invoke the wireshark and examine the various menus  and controls of the tool:

## OUTPUT

<img width="1919" height="940" alt="Screenshot 2025-09-27 095301" src="https://github.com/user-attachments/assets/e91dd257-fa63-4bcf-9123-86866a13e38e" />           


<img width="911" height="858" alt="Screenshot 2025-09-27 102024" src="https://github.com/user-attachments/assets/df9ddfe5-d47a-4904-ab53-b5560ec70853" />

arp poisoning using ethercap

## OUTPUT

<img width="1920" height="1080" alt="Screenshot (220)" src="https://github.com/user-attachments/assets/73d0388e-b0e7-4149-b368-a5784f2f14d6" />

## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
