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
![image](https://github.com/VARSHINI22009118/ARP-Attack-and-Network-Sniffing/assets/119401150/6a5e3f8b-a610-4c15-8247-02ee25463274)


From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:

![image](https://github.com/VARSHINI22009118/ARP-Attack-and-Network-Sniffing/assets/119401150/fd0431f0-466f-46e5-b64d-d69997ac0291)

 dsniff:

In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:

```
NAME : VARSHINI S A
REGISTER NUMBER : 212222100059
```

![image](https://github.com/VARSHINI22009118/ARP-Attack-and-Network-Sniffing/assets/119401150/bace1489-0a4a-4e3e-a11e-aac894e3ec1f)



In Kali issue the following commands:
sudo dsnifff
## OUTPUT:

![image](https://github.com/VARSHINI22009118/ARP-Attack-and-Network-Sniffing/assets/119401150/a26d30da-f79b-47a9-bc04-f29302ef0467)

Invoke the wireshark and examine the various menus  and controls of the tool:

![image](https://github.com/VARSHINI22009118/ARP-Attack-and-Network-Sniffing/assets/119401150/48d10b86-a7c3-4a6b-aa7e-48efd8dd3018)


## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
