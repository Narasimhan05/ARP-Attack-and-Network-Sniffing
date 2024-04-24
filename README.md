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
![Screenshot 2024-04-24 081808](https://github.com/Narasimhan05/ARP-Attack-and-Network-Sniffing/assets/132819871/191b0577-0015-4ca0-8a90-e92dace48196)

From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:

 dsniff:
![Screenshot 2024-04-24 081822](https://github.com/Narasimhan05/ARP-Attack-and-Network-Sniffing/assets/132819871/41c42344-5402-4f4f-b2f1-de325012269e)

In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:

![Screenshot 2024-04-24 081841](https://github.com/Narasimhan05/ARP-Attack-and-Network-Sniffing/assets/132819871/15acafda-b503-48f4-abdc-6c9ddc9b6fc4)

In Kali issue the following commands:
sudo dsnifff
## OUTPUT:

Invoke the wireshark and examine the various menus  and controls of the tool:
![Screenshot 2024-04-24 082016](https://github.com/Narasimhan05/ARP-Attack-and-Network-Sniffing/assets/132819871/a00b16cb-12c9-4ae3-8668-82f2459476d0)


## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
