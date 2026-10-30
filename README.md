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

<img width="1881" height="867" alt="image" src="https://github.com/user-attachments/assets/db008877-6676-42fd-92b3-da83df00c001" />


## Finding IP address:

ping command is available on Windows as well as on Linux OS. Following is the example to find out the IP address of facebook.com.

## output

<img width="900" height="358" alt="image" src="https://github.com/user-attachments/assets/bf4b00eb-1de2-49b7-9771-c212726cf8ab" />




## Finding Hosting Company

get further detail by using ip2location.com website.
## output

<img width="1895" height="855" alt="image" src="https://github.com/user-attachments/assets/46f22c3a-e734-47cb-ba65-6ebc87297bd3" />




## History of the website:

## output
https://web.archive.org/

<img width="1891" height="855" alt="image" src="https://github.com/user-attachments/assets/f2f1872c-7a17-4a50-b8bf-71d8583d6bca" />


# Webserver Fingerprinting:

## Netcat:
```sudo nc example.com 80
GET / HTTP/1.1
Host: example.com
```

### Output

<img width="1421" height="605" alt="image" src="https://github.com/user-attachments/assets/b989777e-ca7b-4c0b-8a20-8573983511d3" />



## nmap:
```
nmap -sL chatgpt.com
```

### Output

<img width="870" height="210" alt="image" src="https://github.com/user-attachments/assets/7f1bbafb-40cc-4770-8cc2-db3e37adc947" />


## Whatweb:
```
whatweb https://chatgpt.com
```

### output

<img width="1906" height="285" alt="image" src="https://github.com/user-attachments/assets/f9abbc7c-21da-44ad-bbfe-69ace4a75dac" />


## httprint:



### output




# Tracing the Location
TCP Traceroute:
sudo traceroute -T www.google.com
## output


## UDP Traceroute:
sudo traceroute -U www.google.com
## output



## ICMP Traceroute:
sudo traceroute  www.google.com
## output






## RESULT:
The information gathering techniques tools/procedure were  identified successfully
