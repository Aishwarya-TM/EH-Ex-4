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
![VirtualBox_Windows 7_15_04_2024_08_01_11](https://github.com/Aishwarya-TM/EH-Ex-4/assets/127846109/99fc3e54-a20a-4ca9-a86e-d1e3d206f06b)


From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:
![VirtualBox_kali-linux-2023 4-virtualbox-amd64_16_04_2024_08_10_12](https://github.com/Aishwarya-TM/EH-Ex-4/assets/127846109/77c57711-057d-4f58-8792-baaed6c91fb1)


 ### dsniff:

In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:
![VirtualBox_kali-linux-2023 4-virtualbox-amd64_16_04_2024_09_41_50](https://github.com/Aishwarya-TM/EH-Ex-4/assets/127846109/20895c9c-4049-4846-b459-93b38cd38ebf)

In Kali issue the following commands:
sudo dsnifff
## OUTPUT:
 ![VirtualBox_kali-linux-2023 4-virtualbox-amd64_16_04_2024_09_41_25](https://github.com/Aishwarya-TM/EH-Ex-4/assets/127846109/3d5bd6d7-8c21-4e7b-b431-f013bc661ce8)

Invoke the wireshark and examine the various menus  and controls of the tool:

![VirtualBox_kali-linux-2023 4-virtualbox-amd64_16_04_2024_10_00_43](https://github.com/Aishwarya-TM/EH-Ex-4/assets/127846109/b7f6d8e7-5592-42c4-acca-c18bffe2e4db)

### Ettercap:
Ettercap supports active and passive dissection of many protocols (even encrypted ones) and includes many feature for network and host analysis.
Ettercap can be used as sniffing tool as illustrated below:
![VirtualBox_kali-linux-2023 4-virtualbox-amd64_16_04_2024_09_58_46](https://github.com/Aishwarya-TM/EH-Ex-4/assets/127846109/bfcb6ee7-4d96-4351-926c-c90dd8c1e906)


## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
