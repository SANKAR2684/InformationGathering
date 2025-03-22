# InformationGathering
Information Gathering Techiques

# To perform information gathering techniques

# AIM:

To perform information gathering techniques using kali linux 

## STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode

### Step 2:

Investigate on the various categories of tools as follows:

### Step 3:
Open terminal/browser and try execute necessary commands/use url to perform information gathering


## OUTPUT:
Who is:
OUTPUT:
![Alt text](image.png)

Finding IP Address:

IP Address of FACEBOOK.com
OUTPUT:
![Alt text](image-9.png)

Finding Hosting Company
get further detail by using ip2location.com website.

OUTPUT:
![Alt text](image-1.png)

Histoey Of The Website:
OUTPUT:
![Alt text](image-2.png)


Netcat:
OUTPUT:
sudo nc google.com 80
GET / HTTP/1.1
Host: google.com

OUTPUT:
![Alt text](image-3.png)

NMAP:
OUTPUT:
![Alt text](image-4.png)

Whatweb
OUTPUT:
![Alt text](image-5.png)

Whatweb -v 3 172.17.62.8
![Alt text](<meta connect.png>)

Httprint
OUTPUT:
![268918245-60d425cc-5f76-41f7-8634-261b13e42b66](https://github.com/user-attachments/assets/63a77d36-f93a-46e0-b88d-de87201d6e26)




Tracing The Location
TCP Traceroute:
sudo -T ww.gmail.com

OUTPUT:
![Alt text](<sudo traceroute-1.png>)

UDP Traceroute:
sudo traceroute -U www.gmail.com
OUTPUT:

![Alt text](image-7.png)

ICMP Traceroute:
sudo traceroute  www.gmail.com
OUTPUT:
![Alt text](image-8.png)



## RESULT:
The information gathering techniques tools/procedure were  identified successfully
