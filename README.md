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

## Pen Test Tools Categories:  

Following Categories of pen test tools are identified for information gathering:

Footprinting is a part of the reconnaissance process which is used for gathering possible information about a target computer system or network.
http://www.whois.com/whois website to get detailed information about a domain name information including its owner, its registrar, date of registration, expiry, name server, owner's contact information, etc.

## OUTPUT:



## Finding IP address:
ping command is available on Windows as well as on Linux OS. Following is the example to find out the IP address of nvidia.com
## output

<img width="1917" height="1199" alt="Screenshot 2026-08-06 142932" src="https://github.com/user-attachments/assets/ce24fb6f-adb0-431d-8b3c-9745fe5ce4b4" />

## Finding Hosting Company
get further detail by using ip2location.com website.
## output
<img width="765" height="1073" alt="image" src="https://github.com/user-attachments/assets/57276655-9002-4e14-a956-dafc0ee9002b" />
<img width="735" height="668" alt="image" src="https://github.com/user-attachments/assets/baf6aac6-8f1a-40cb-a7ab-385024962251" />



## History of the website:
## output
https://web.archive.org/
<img width="1312" height="1152" alt="image" src="https://github.com/user-attachments/assets/dcd9f060-cf41-4a20-9290-a5339497616c" />
<img width="1502" height="1142" alt="image" src="https://github.com/user-attachments/assets/83cf7f3c-2abb-4cf8-8993-5656a11582b7" />


# Webserver Fingerprinting:
## output

<img width="1076" height="1152" alt="image" src="https://github.com/user-attachments/assets/b8d7b469-58bc-4886-81c7-393f2ffb8246" />

## Netcat:
## output

sudo nc www.nvidia.com 80
GET / HTTP/1.1
Host: www.nvidia.com

<img width="642" height="437" alt="image" src="https://github.com/user-attachments/assets/a145ed10-a9e6-4ee2-ab98-a13d58264ec2" />
<img width="630" height="522" alt="image" src="https://github.com/user-attachments/assets/022d81d2-41e9-4735-b8c2-477ec434a6e5" />


## nmap:
## output
<img width="648" height="397" alt="image" src="https://github.com/user-attachments/assets/276bb897-8ca7-45e2-af6e-ef13a9d74ee3" />


## Whatweb
## output
<img width="630" height="502" alt="image" src="https://github.com/user-attachments/assets/982a2a16-320e-4743-a100-50f4fe903052" />





# Tracing the Location
TCP Traceroute:
sudo traceroute -T www.nvidia.com
## output
<img width="641" height="262" alt="image" src="https://github.com/user-attachments/assets/14acdc0a-e31e-4523-8e55-5b7082a14a0f" />


## UDP Traceroute:
sudo traceroute -U www.nvidia.com
## output
<img width="632" height="396" alt="image" src="https://github.com/user-attachments/assets/4c9f9b3b-762e-4269-8727-2afb44e9f18d" />



## ICMP Traceroute:
sudo traceroute  www.nvidia.com
## output
<img width="632" height="427" alt="image" src="https://github.com/user-attachments/assets/d9475093-a388-46e2-aec6-d6d1c40f186d" />






## RESULT:
The information gathering techniques tools/procedure were  identified successfully
