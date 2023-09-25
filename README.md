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


Pen Test Tools Categories:
Following Categories of pen test tools are identified for information gathering:

Footprinting is a part of the reconnaissance process which is used for gathering possible information about a target computer system or network.

http://www.whois.com/whois website to get detailed information about a domain name information including its owner, its registrar, date of registration, expiry, name server, owner's contact information, etc.


## OUTPUT:
![image](https://github.com/Subhikshaa13/InformationGathering/assets/118787344/3febe2f5-75d0-4948-971a-d39f1ac394c7)

Finding IP address:
ping command is available on Windows as well as on Linux OS. Following is the example to find out the IP address of saveetha.ac.in.

ping saveetha.ac.in
![image](https://github.com/Subhikshaa13/InformationGathering/assets/118787344/0ddcf0a3-6d84-4209-b7ba-c205e3ecb88a)

Finding Hosting Company:
get further detail by using ip2location.com website.

![image](https://github.com/Subhikshaa13/InformationGathering/assets/118787344/80bfbd1e-5734-4c70-81d0-48bf3ac4e3bc)

History of the website:
Output:

![image](https://github.com/Subhikshaa13/InformationGathering/assets/118787344/2bdaf706-8f23-42ad-b566-0ffafc310e23)

Webserver Fingerprinting:
Netcat:
nc 172.17.52.118 80

OUTPUT:
![image](https://github.com/Subhikshaa13/InformationGathering/assets/118787344/b373e069-fb01-4226-8e7f-852df7542202)

nmap:
nmap -p 21 -sV --script=banner ftp.vim.org

OUTPUT:
![image](https://github.com/Subhikshaa13/InformationGathering/assets/118787344/ecf3301c-87e0-4912-b72c-4af54353aebc)

Whatweb:
whatweb infosys.com

whatweb zoho.com

whatweb -v -a 3 172.17.52.201

![image](https://github.com/Subhikshaa13/InformationGathering/assets/118787344/6cd39c62-2929-4c64-a6ad-60c607d71b5b)

httprint:
httprint -h 172.17.52.201 -s /usr/share/httprint/signatures.txt -P0 |more

OUTPUT:

![image](https://github.com/Subhikshaa13/InformationGathering/assets/118787344/62d310bd-1708-460d-8800-0433a2169fad)

Tracing the Location
TCP Traceroute:
sudo traceroute -T www.saveetha.ac.in

OUTPUT:


![image](https://github.com/Subhikshaa13/InformationGathering/assets/118787344/f1d81070-fdfe-4782-a441-e4bb7881ddf0)

UDP Traceroute:
sudo traceroute -U www.saveetha.ac.in

OUTPUT:
![image](https://github.com/Subhikshaa13/InformationGathering/assets/118787344/fd67a4ca-f3a1-4c1d-a5ba-6e2005b82cd3)

ICMP Traceroute:
sudo traceroute  www.saveetha.ac.in

OUTPUT:

![image](https://github.com/Subhikshaa13/InformationGathering/assets/118787344/2d825cca-8dab-4fc6-a99b-a8a9a9ff7dee)











## RESULT:
The information gathering techniques tools/procedure were  identified successfully
