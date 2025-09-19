# Enumeration
Enumeration Techniques

# Explore Google hacking and enumeration 

```
Rithika R
212224240136
```

# AIM:

To use Google for gathering information and perform enumeration of targets

## STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode

### Step 2:

Investigate on the various Google hacking keywords and enumeration tools as follows:


### Step 3:
Open terminal and try execute some kali linux commands

## Pen Test Tools Categories:  

Following Categories of pen test tools are identified:
Information Gathering.

Google Hacking:

Google hacking, also known as Google dorking, is a technique that involves using advanced operators to perform targeted searches on Google. These operators can be used to search for specific types of information, such as sensitive data that may have been inadvertently exposed on the web. Here are some advanced operators that can be used for Google hacking:
<img width="1539" height="909" alt="Screenshot 2025-09-19 132641" src="https://github.com/user-attachments/assets/4ab0aed6-82a0-4bba-90b4-7ac97a791ea5" />

site: This operator allows you to search for pages that are within a specific website or domain. For example, "site:example.com" would search for pages that are on the example.com domain.
Following searches for all the sites that is in the domain yahoo.com
<img width="1725" height="908" alt="Screenshot 2025-09-19 132731" src="https://github.com/user-attachments/assets/e1b5df8b-48e9-4e72-8cdd-f404a2182b3b" />

filetype: This operator allows you to search for files of a specific type. For example, "filetype:pdf" would search for all PDF files.
Following searches for pdf file in the domain yahoo.com

<img width="1328" height="905" alt="Screenshot 2025-09-19 133021" src="https://github.com/user-attachments/assets/7ea36ec5-e86f-4fe9-b55d-b1417e6cdd46" />


intext: This operator allows you to search for pages that contain specific text within the body of the page. For example, "intext:password" would search for pages that contain the word "password" within the body of the page.
<img width="1319" height="899" alt="Screenshot 2025-09-19 133206" src="https://github.com/user-attachments/assets/46a8b2b2-4fff-4f4b-85f7-f511efa11891" />



inurl: This operator allows you to search for pages that contain specific text within the URL. For example, "inurl:admin" would search for pages that contain the word "admin" within the URL.
<img width="1314" height="909" alt="Screenshot 2025-09-19 133245" src="https://github.com/user-attachments/assets/14d0c272-1dbe-46c9-9d4f-0ae44b466557" />

intitle: This operator allows you to search for pages that contain specific text within the title tag. For example, "intitle:index of" would search for pages that contain "index of" within the title tag.
<img width="1538" height="903" alt="Screenshot 2025-09-19 133441" src="https://github.com/user-attachments/assets/95b419b6-846f-4dfb-9e53-2d0e5439a91c" />


link: This operator allows you to search for pages that link to a specific URL. For example, "link:example.com" would search for pages that link to the example.com domain.
<img width="1730" height="916" alt="Screenshot 2025-09-19 133551" src="https://github.com/user-attachments/assets/84462e0f-477a-4528-9c5f-ad45757d60af" />


cache: This operator allows you to view the cached version of a page. For example, "cache:example.com" would show the cached version of the example.com website.

 <img width="1605" height="854" alt="image" src="https://github.com/user-attachments/assets/1c22a0f2-5fc1-4372-9d64-cd8a5d255996" />

#DNS Enumeration


##DNS Recon
provides the ability to perform:
Check all NS records for zone transfers
Enumerate general DNS records for a given domain (MX, SOA, NS, A, AAAA, SPF , TXT)
Perform common SRV Record Enumeration
Top level domain expansion
## OUTPUT:


<img width="746" height="603" alt="image" src="https://github.com/user-attachments/assets/bb21a594-6fae-4950-9a29-98392372574c" />





## dnsenum
Dnsenum is a multithreaded perl script to enumerate DNS information of a domain and to discover non-contiguous ip blocks. The main purpose of Dnsenum is to gather as much information as possible about a domain. The program currently performs the following operations:

Get the host’s addresses (A record).
Get the namservers (threaded).
Get the MX record (threaded).
Perform axfr queries on nameservers and get BIND versions(threaded).
Get extra names and subdomains via google scraping (google query = “allinurl: -www site:domain”).
Brute force subdomains from file, can also perform recursion on subdomain that have NS records (all threaded).
Calculate C class domain network ranges and perform whois queries on them (threaded).
Perform reverse lookups on netranges (C class or/and whois netranges) (threaded).
Write to domain_ips.txt file ip-blocks.
This program is useful for pentesters, ethical hackers and forensics experts. It also can be used for security tests.
<img width="736" height="510" alt="image" src="https://github.com/user-attachments/assets/95163872-8224-47b5-adeb-68db81607fb4" />

## smtp-user-enum
Username guessing tool primarily for use against the default Solaris SMTP service. Can use either EXPN, VRFY or RCPT TO.


In metasploit list all the usernames using head /etc/passwd or cat /etc/passwd:

select any username in the first column of the above file and check the same


#Telnet for smtp enumeration
Telnet allows to connect to remote host based on the port no. For smtp port no is 25
telnet <host address> 25 to connect
and issue appropriate commands
  
 ##Output
  <img width="747" height="415" alt="image" src="https://github.com/user-attachments/assets/df055f43-0a50-48ec-ab9e-9e27218eef4d" />
  

## nmap –script smtp-enum-users.nse <hostname>

The smtp-enum-users.nse script attempts to enumerate the users on a SMTP server by issuing the VRFY, EXPN or RCPT TO commands. The goal of this script is to discover all the user accounts in the remote system.


## OUTPUT:

<img width="680" height="142" alt="image" src="https://github.com/user-attachments/assets/bf2982f5-e7bb-4537-9a7d-bc5bfed15ad2" />
## RESULT:
The Google hacking keywords and enumeration tools were identified and executed successfully

