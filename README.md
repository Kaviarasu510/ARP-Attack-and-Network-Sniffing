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

![4 1](https://github.com/Kaviarasu510/ARP-Attack-and-Network-Sniffing/assets/119392695/420264c3-4973-4731-b010-637af1d46eaa)

From kali linux issue the command :

sudo arpspoof -i eth0 -t <target system> <gateway>

## OUTPUT:

![4 2](https://github.com/Kaviarasu510/ARP-Attack-and-Network-Sniffing/assets/119392695/5911dcaa-901a-40d6-9887-7e806426430f)

## dsniff:

In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org

## OUTPUT:

![4 3](https://github.com/Kaviarasu510/ARP-Attack-and-Network-Sniffing/assets/119392695/8b0c09bb-39e1-42a7-996f-ba46ec4080a4)

In Kali issue the following commands:

sudo dsnifff

## OUTPUT:

![4 4](https://github.com/Kaviarasu510/ARP-Attack-and-Network-Sniffing/assets/119392695/8039f393-c3f0-4a82-a1b4-e62d6dfafd75)

Invoke the wireshark and examine the various menus  and controls of the tool. Also following shows how wireshark can be used as sniffing tool.

![4 5](https://github.com/Kaviarasu510/ARP-Attack-and-Network-Sniffing/assets/119392695/362cc9e8-5ff6-4901-a141-d37aad9f5502)

## Ettercap

Ettercap supports active and passive dissection of many protocols (even encrypted ones) and includes many feature for network and host analysis.

Ettercap can be used as sniffing tool as illustrated below:

![4 6](https://github.com/Kaviarasu510/ARP-Attack-and-Network-Sniffing/assets/119392695/d0379054-a60f-4a5b-afc9-0889e4c74855)

## RESULT:

The kali linux tools for ARP Attack and Network Sniffing were identified successfully

