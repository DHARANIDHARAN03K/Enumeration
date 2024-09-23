# Enumeration
Enumeration Techniques

# Explore Google hacking and enumeration 

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


### Google Hacking:
![site](https://github.com/Reebak04/Enumeration/assets/118364993/38cbd459-719e-49d9-a79b-a427a6235289)


Google hacking:

site: 
### filetype: 
![sf](https://github.com/Reebak04/Enumeration/assets/118364993/a8c4f70e-d872-4f91-b339-003b3e9a5266)




### intext:
![intext](https://github.com/Reebak04/Enumeration/assets/118364993/ef8cc91f-4784-4877-9a8d-a60307d07079)



### inurl: 
![admin](https://github.com/Reebak04/Enumeration/assets/118364993/71f41b2c-b972-48da-9491-ec51785f25df)


### intitle: 
![Screenshot 2023-09-12 223748](https://github.com/Reebak04/Enumeration/assets/118364993/4f142752-1c1b-4437-a103-6429215794a8)

### link:
![link](https://github.com/Reebak04/Enumeration/assets/118364993/998825ee-d0c6-42cd-be21-3a02a700f1df)

### cache:
![cache](https://github.com/Reebak04/Enumeration/assets/118364993/09b114f0-72e3-4d1d-8bba-19856bc5a088)

 
#DNS Enumeration


##DNS Recon
provides the ability to perform:
Check all NS records for zone transfers
Enumerate general DNS records for a given domain (MX, SOA, NS, A, AAAA, SPF , TXT)
Perform common SRV Record Enumeration
Top level domain expansion
## OUTPUT:







##dnsenum
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


##smtp-user-enum
Username guessing tool primarily for use against the default Solaris SMTP service. Can use either EXPN, VRFY or RCPT TO.


In metasploit list all the usernames using head /etc/passwd or cat /etc/passwd:

select any username in the first column of the above file and check the same


#Telnet for smtp enumeration
Telnet allows to connect to remote host based on the port no. For smtp port no is 25
telnet <host address> 25 to connect
and issue appropriate commands
  
 ##Output
  
  

## nmap –script smtp-enum-users.nse <hostname>

The smtp-enum-users.nse script attempts to enumerate the users on a SMTP server by issuing the VRFY, EXPN or RCPT TO commands. The goal of this script is to discover all the user accounts in the remote system.


## OUTPUT:


## RESULT:
The Google hacking keywords and enumeration tools were identified and executed successfully

