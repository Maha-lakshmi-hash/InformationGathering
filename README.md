InformationGathering Information Gathering Techiques To perform information gathering techniques AIM: To perform information gathering techniques using kali linux STEPS:

Step 1:

Install kali linux either in partition or virtual box or in live mode

Step 2: 

Investigate on the various categories of tools as follows: 

Step 3:

Open terminal/browser and try execute necessary commands/use url to perform information gathering Pen Test Tools Categories: Following Categories of pen test tools are identified for information gathering: Footprinting is a part of the reconnaissance process which is used for gathering possible information about a target computer system or network. http://www.whois.com/whois website to get detailed information about a domain name information including its owner, its registrar, date of registration, expiry, name server, owner's contact information, etc.

OUTPUT:

<img width="985" height="519" alt="image" src="https://github.com/user-attachments/assets/7a67261e-d47d-4acd-a79f-4029ddeb68c6" />

inding IP address: 

ping command is available on Windows as well as on Linux OS. Following is the example to find out the IP address of facebook.com

OUTPUT:

<img width="635" height="518" alt="image" src="https://github.com/user-attachments/assets/2ee1deaf-64b9-42ad-b514-42e7a699ff67" />

Finding Hosting Company get further detail by using ip2location.com website. 

OUTPUT:

<img width="1129" height="635" alt="image" src="https://github.com/user-attachments/assets/3ca660d2-3f82-4af2-b96b-18b70df73f9f" />

<img width="1093" height="494" alt="image" src="https://github.com/user-attachments/assets/ac3bcfd8-472f-437f-9423-666e0f04aa9d" />

History of the website: 

OUTPUT:

https://web.archive.org/

<img width="1243" height="664" alt="image" src="https://github.com/user-attachments/assets/b3e20010-b737-4958-8d96-12c9d90eaa17" />

Webserver Fingerprinting:

Netcat:

sudo nc example.com 80 GET / HTTP/1.1 
Host: example.com

##output

nmap:

OUTPUT:

<img width="627" height="205" alt="image" src="https://github.com/user-attachments/assets/1a895d2f-6015-4d75-a814-a03fb4971a0d" />

Whatweb

OUTPUT:

<img width="604" height="421" alt="image" src="https://github.com/user-attachments/assets/0be48d27-e958-4e41-b366-58821d6208ee" />

httprint 

OUTPUT:

<img width="767" height="678" alt="image" src="https://github.com/user-attachments/assets/e11b40b0-7dc4-4746-8b7f-4c3cf3d4f4fb" />

racing the Location 

TCP Traceroute: 3sudo traceroute wikipedia.org

<img width="929" height="512" alt="image" src="https://github.com/user-attachments/assets/12f64910-7bd3-4a72-9821-25c45f24d6dc" />


DP Traceroute: 

sudo traceroute -T www.microsoft.com

OUTPUT:

<img width="766" height="230" alt="image" src="https://github.com/user-attachments/assets/fdc7f6af-4e39-477c-ad19-e5183a18345e" />

CMP Traceroute: 

sudo traceroute -U www.twitter.com

OUTPUT:

<img width="635" height="569" alt="Screenshot 2026-08-24 123521" src="https://github.com/user-attachments/assets/d15679a5-d4b4-49ff-98b1-94f09040b1b1" />

RESULT:

The information gathering techniques tools/procedure were identified successfully
