# Enumeration
Enumeration Techniques

# Explore Google hacking and enumeration 

### NAME:S.NAVEEN
### REG NO:212223240106

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
![Screenshot 2024-09-23 152907](https://github.com/user-attachments/assets/7fa9c98e-d3c2-4f2d-9e51-1f02c3319433)



filetype: This operator allows you to search for files of a specific type. For example, "filetype:pdf" would search for all PDF files.
Following searches for pdf file in the domain yahoo.com
## Output:
![Screenshot 2024-09-23 153127](https://github.com/user-attachments/assets/be3f2fd7-e341-48bb-9839-8aa2630374bc)




intext: This operator allows you to search for pages that contain specific text within the body of the page. For example, "intext:password" would search for pages that contain the word "password" within the body of the page.
## Output:
![Screenshot 2024-09-23 153146](https://github.com/user-attachments/assets/df63c3c5-0338-466c-ab80-7f07691c33f6)



inurl: This operator allows you to search for pages that contain specific text within the URL. For example, "inurl:admin" would search for pages that contain the word "admin" within the URL.
## Ouput:
![image](https://github.com/user-attachments/assets/397a287f-268f-41ce-b7a7-4f8532bb30eb)


intitle: This operator allows you to search for pages that contain specific text within the title tag. For example, "intitle:index of" would search for pages that contain "index of" within the title tag.
## Output:
![Screenshot 2024-09-23 153410](https://github.com/user-attachments/assets/0d1b8d7f-134e-455f-9b6c-07a5b5656f9b)

link: This operator allows you to search for pages that link to a specific URL. For example, "link:example.com" would search for pages that link to the example.com domain.
## Output:
![image](https://github.com/user-attachments/assets/c1aed59e-86f4-44e1-b528-216bcf1ba0d3)



cache: This operator allows you to view the cached version of a page. For example, "cache:example.com" would show the cached version of the example.com website.
## Output:
![Screenshot 2024-09-23 185042](https://github.com/user-attachments/assets/d16cb616-3c81-43b3-bb2b-d40fcbb821df)

# DNS Enumeration


## DNS Recon
provides the ability to perform:
Check all NS records for zone transfers
Enumerate general DNS records for a given domain (MX, SOA, NS, A, AAAA, SPF , TXT)
Perform common SRV Record Enumeration
Top level domain expansion
## OUTPUT:

![6](https://github.com/user-attachments/assets/98097dc1-8a7c-49b6-8004-50d4d714cc7f)
![7](https://github.com/user-attachments/assets/20e3ac1d-6729-4c20-bf1e-84b54bcb1466)




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


![8](https://github.com/user-attachments/assets/1beda767-a909-428e-bc53-2c4db92cca90)










## smtp-user-enum



![9](https://github.com/user-attachments/assets/979f7bcc-16dc-4008-8682-86cbdeb5d2ca)


# Telnet for smtp enumeration
Telnet allows to connect to remote host based on the port no. For smtp port no is 25
telnet <host address> 25 to connect
and issue appropriate commands
  
 ## Output

![10](https://github.com/user-attachments/assets/effec57f-10fb-4841-9a57-917667a85fb4)

## nmap –script smtp-enum-users.nse <hostname>

![11](https://github.com/user-attachments/assets/f36636bb-0819-4038-8473-29ebf7f9b8bf)


  

## RESULT:
The Google hacking keywords and enumeration tools were identified and executed successfully

