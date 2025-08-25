# Ex-02 InformationGathering
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

## Architecture Diagram
```
                      +-------------------------+
                      |     Attacker System     |
                      |     (Kali Linux)        |
                      +-----------+-------------+
                                  |
                                  | Terminal / Browser
                                  | Executes Recon Tools
                                  v
      +------------------- Passive Recon --------------------+
      |                                                     |
      |  +----------------+     +------------------------+  |
      |  |   WHOIS Query  | --> |    Domain Registrars    |  |
      |  +----------------+     +------------------------+  |
      |                                                     |
      |  +----------------+     +------------------------+  |
      |  |   DNS Enum     | --> |     Public DNS Servers  |  |
      |  +----------------+     +------------------------+  |
      |                                                     |
      +-----------------------------------------------------+

                                  |
                                  v

      +------------------ Active Recon ----------------------+
      |                                                     |
      |  +----------------+     +------------------------+  |
      |  |   Nmap Scan    | --> |  Target Host/Network    |  |
      |  +----------------+     +------------------------+  |
      |                                                     |
      |  +----------------+     +------------------------+  |
      |  | WhatWeb, Wapp | --> |   Target Web Application |  |
      |  +----------------+     +------------------------+  |
      |                                                     |
      |  +----------------+     +------------------------+  |
      |  | theHarvester   | --> |     Search Engines      |  |
      |  +----------------+     +------------------------+  |
      +-----------------------------------------------------+

                                  |
                                  v
                    +-----------------------------+
                    |     Collected Information   |
                    | - IPs, Subdomains           |
                    | - Open Ports & Services     |
                    | - Technology Stack          |
                    | - Emails, Metadata          |
                    +-----------------------------+
```

## OUTPUT:
### Whois
<img width="1788" height="902" alt="image" src="https://github.com/user-attachments/assets/110ef97d-d3ba-4bf0-ad20-b2ffed5eba78" />


### Finding Hosting Company :
<img width="1138" height="910" alt="image" src="https://github.com/user-attachments/assets/100df5f6-cff5-42eb-bc3e-f68d6048d639" />


### History of the website :
<img width="1786" height="847" alt="image" src="https://github.com/user-attachments/assets/76fe1fa1-7b1f-484e-94a2-f4928869f7a2" />


### ping command :
<img width="1903" height="896" alt="image" src="https://github.com/user-attachments/assets/86a8a584-5af1-4c57-9126-9ae96fec7b04" />


### netcat :

### nmap :
<img width="955" height="323" alt="image" src="https://github.com/user-attachments/assets/1e4e53f0-40eb-4215-ab73-b27f393968d3" />



### whatweb :
<img width="938" height="758" alt="image" src="https://github.com/user-attachments/assets/1ade2200-c513-4eea-9421-d0b14e4cd512" />


### httprint :
<img width="1648" height="836" alt="image" src="https://github.com/user-attachments/assets/f8330fac-a89e-4d6e-9476-feb769abcb7f" />


### TCP traceroute :
<img width="1034" height="148" alt="image" src="https://github.com/user-attachments/assets/d3e8a594-0409-4901-bbee-70efc3f65a58" />
<img width="1047" height="767" alt="image" src="https://github.com/user-attachments/assets/addee6e1-b4d0-46c2-b95e-47413e9f67cb" />


### UDP traceroute :
<img width="1028" height="773" alt="image" src="https://github.com/user-attachments/assets/a04f3882-3c68-496b-834b-53d29e32a07a" />



## RESULT:
The information gathering techniques tools/procedure were  identified successfully
