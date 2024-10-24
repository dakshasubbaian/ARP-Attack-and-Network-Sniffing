### Date:23.10.2024
# Ex-4: ARP-Attack-and-Network-Sniffing
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
## ARP spoofing: 
A hacker sends fake ARP packets that link an attacker's MAC address with an IP of a computer already on the LAN. 
Boot kali and Windows7 virtual machines.
In windows 7 give the command arp -a
## OUTPUT:

![1)](https://github.com/user-attachments/assets/974e8b81-65f9-4736-871a-32ecdb3bdf13)

</br>
From kali linux issue the command :

```
sudo arpspoof -i eth0 -t <target system> <gateway>
```
  
## Output:
![arp](https://github.com/user-attachments/assets/9833dc4d-d5fe-4e8b-ac42-77fbbca1f4a4)



## dsniff:
In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org

## Output:

In Kali issue the following commands:
```
sudo dsniff
```


![ftp](https://github.com/user-attachments/assets/ed1fe4b1-def0-430c-8a74-b32cb58d7ac3)

## Output:

![dns](https://github.com/user-attachments/assets/f872106b-c084-4498-92e5-0463a9d4489d)


## Wireshark:
Invoke the wireshark and examine the various menus  and controls of the tool:
## Output:
![Screenshot 2024-10-22 210736](https://github.com/user-attachments/assets/5b4457bb-892c-4785-a0af-0c104d9756a4)

## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully.
