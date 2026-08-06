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

<img width="1919" height="1199" alt="Screenshot 2026-08-06 143347" src="https://github.com/user-attachments/assets/345192c7-82c3-4b36-8a37-8bc7c7df9aac" />

## History of the website:
## output
https://web.archive.org/

<img width="1919" height="1199" alt="Screenshot 2026-08-06 143512" src="https://github.com/user-attachments/assets/c0fd0519-84cb-4d25-9748-8b5286186954" />

# Webserver Fingerprinting:
## output

<img width="1919" height="1199" alt="Screenshot 2026-08-06 143701" src="https://github.com/user-attachments/assets/e01e1467-04d9-471a-a90c-d5545a19fe9a" />

## Netcat:
## output

sudo nc www.nvidia.com 80
GET / HTTP/1.1
Host: www.nvidia.com

<img width="1919" height="1199" alt="Screenshot 2026-08-06 144244" src="https://github.com/user-attachments/assets/11090db8-da90-446a-853a-cbb871d70331" />

## nmap:
## output

<img width="1919" height="1199" alt="Screenshot 2026-08-06 144416" src="https://github.com/user-attachments/assets/5c04527a-db9a-4ce1-b152-635d99c8fcac" />

## Whatweb
## output

<img width="1919" height="1199" alt="Screenshot 2026-08-06 144515" src="https://github.com/user-attachments/assets/41712b4d-9acd-4099-b82a-5e4bee96c354" />

# Tracing the Location
TCP Traceroute:
sudo traceroute -T www.nvidia.com
## output

<img width="1919" height="1199" alt="Screenshot 2026-08-06 144634" src="https://github.com/user-attachments/assets/aec75ead-6809-475c-9b11-2d907bb8f993" />

## UDP Traceroute:
sudo traceroute -U www.nvidia.com
## output

<img width="1919" height="1199" alt="Screenshot 2026-08-06 144803" src="https://github.com/user-attachments/assets/30059e7f-bd18-4e8d-86f8-715d7b13d399" />

## ICMP Traceroute:
sudo traceroute  www.nvidia.com
## output

<img width="1919" height="1199" alt="Screenshot 2026-08-06 144909" src="https://github.com/user-attachments/assets/e80c9a8d-57ab-4e41-8938-9c95dad33bba" />

## RESULT:
The information gathering techniques tools/procedure were  identified successfully
