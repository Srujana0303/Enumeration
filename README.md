```
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

Following Categories of pen test tools are identified:
Information Gathering.

Google Hacking:

Google hacking, also known as Google dorking, is a technique that involves using advanced operators to perform targeted searches on Google. These operators can be used to search for specific types of information, such as sensitive data that may have been inadvertently exposed on the web. Here are some advanced operators that can be used for Google hacking:

site: This operator allows you to search for pages that are within a specific website or domain. For example, "site:example.com" would search for pages that are on the example.com domain.
Following searches for all the sites that is in the domain yahoo.com


## Output:



![image](https://github.com/Srujana0303/Enumeration/assets/132996836/e0fb6b1f-609a-4ad2-ba5a-2f2217c51bfd)



filetype: This operator allows you to search for files of a specific type. For example, "filetype:pdf" would search for all PDF files.
Following searches for pdf file in the domain yahoo.com




## Output:



![image](https://github.com/Srujana0303/Enumeration/assets/132996836/19bd5e96-03ef-4f9d-9513-4d20e5ca8749)




intext: This operator allows you to search for pages that contain specific text within the body of the page. For example, "intext:password" would search for pages that contain the word "password" within the body of the page.



## Output:



![image](https://github.com/Srujana0303/Enumeration/assets/132996836/7c70a75b-e13d-4415-a628-2f7c35a08732)



inurl: This operator allows you to search for pages that contain specific text within the URL. For example, "inurl:admin" would search for pages that contain the word "admin" within the URL.




## Output:



![image](https://github.com/Srujana0303/Enumeration/assets/132996836/8d6cd779-0263-4098-b1dc-31052eb9625b)




intitle: This operator allows you to search for pages that contain specific text within the title tag. For example, "intitle:index of" would search for pages that contain "index of" within the title tag.



## Output:



![image](https://github.com/Srujana0303/Enumeration/assets/132996836/3755b63f-9b6d-4b3d-8aaf-38a7a1939675)



link: This operator allows you to search for pages that link to a specific URL. For example, "link:example.com" would search for pages that link to the example.com domain.



## Output:



![image](https://github.com/Srujana0303/Enumeration/assets/132996836/c94bbb4e-c729-4e7b-9af6-4784eb05d407)



cache: This operator allows you to view the cached version of a page. For example, "cache:example.com" would show the cached version of the example.com website.



 ## Output:



![image](https://github.com/Srujana0303/Enumeration/assets/132996836/5d6ce1dd-b1c6-4ce9-80c5-034f5bdd400d)



 #DNS Enumeration





##DNS Recon



provides the ability to perform:
Check all NS records for zone transfers
Enumerate general DNS records for a given domain (MX, SOA, NS, A, AAAA, SPF , TXT)
Perform common SRV Record Enumeration
Top level domain expansion



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
  

  


  

## nmap –script smtp-enum-users.nse <hostname>




The smtp-enum-users.nse script attempts to enumerate the users on a SMTP server by issuing the VRFY, EXPN or RCPT TO commands. The goal of this script is to discover all the user accounts in the remote system.




## RESULT:


The Google hacking keywords and enumeration tools were identified and executed successfully

```
