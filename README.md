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
![Screenshot 2024-04-16 082755](https://github.com/chandrumathiyazhagan/Enumeration/assets/119393023/4371d1e8-d99d-4fbd-bfe2-624346784ffe)

filetype: This operator allows you to search for files of a specific type. For example, "filetype:pdf" would search for all PDF files.
Following searches for pdf file in the domain yahoo.com
## Output:
![Screenshot 2024-04-16 082901](https://github.com/chandrumathiyazhagan/Enumeration/assets/119393023/70a66347-0fd3-44dc-bc45-5f04f95e24c9)

intext: This operator allows you to search for pages that contain specific text within the body of the page. For example, "intext:password" would search for pages that contain the word "password" within the body of the page.
## Output:
![Screenshot 2024-04-16 083028](https://github.com/chandrumathiyazhagan/Enumeration/assets/119393023/e38e4f21-f22f-4d70-8400-ff98f3025006)

inurl: This operator allows you to search for pages that contain specific text within the URL. For example, "inurl:admin" would search for pages that contain the word "admin" within the URL.
## Ouput:
![Screenshot 2024-04-16 083127](https://github.com/chandrumathiyazhagan/Enumeration/assets/119393023/40efb33c-f451-4bee-850a-855ad5543064)

intitle: This operator allows you to search for pages that contain specific text within the title tag. For example, "intitle:index of" would search for pages that contain "index of" within the title tag.
## Output:
![Screenshot 2024-04-16 083220](https://github.com/chandrumathiyazhagan/Enumeration/assets/119393023/d3f4b15b-9329-4791-b51b-419dce762b97)

link: This operator allows you to search for pages that link to a specific URL. For example, "link:example.com" would search for pages that link to the example.com domain.
## Output:
![Screenshot 2024-04-16 083352](https://github.com/chandrumathiyazhagan/Enumeration/assets/119393023/24b52a5a-c634-4ff6-9c0b-bd74f104358b)

cache: This operator allows you to view the cached version of a page. For example, "cache:example.com" would show the cached version of the example.com website.
## Output:
![Screenshot 2024-04-16 083537](https://github.com/chandrumathiyazhagan/Enumeration/assets/119393023/fc76cb29-df31-4b3e-8c64-80d65ddd584f)

# DNS Enumeration

## DNS Recon
provides the ability to perform:
Check all NS records for zone transfers
Enumerate general DNS records for a given domain (MX, SOA, NS, A, AAAA, SPF , TXT)
Perform common SRV Record Enumeration
Top level domain expansion
## OUTPUT:
![5](https://github.com/chandrumathiyazhagan/Enumeration/assets/119393023/86e91d59-b86c-4455-9370-cbb3b92a4d11)

![2](https://github.com/chandrumathiyazhagan/Enumeration/assets/119393023/87d26294-d5be-40b2-b1f7-70b9db10e9f3)

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

![IMG-20240416-WA0004](https://github.com/chandrumathiyazhagan/Enumeration/assets/119393023/5cbabc29-ddc3-4b83-a676-49dc17627f08)

## smtp-user-enum
![IMG-20240416-WA0006](https://github.com/chandrumathiyazhagan/Enumeration/assets/119393023/ea970bfd-2fa8-4da7-a142-45a4953ca528)

## Telnet for smtp enumeration
Telnet allows to connect to remote host based on the port no. For smtp port no is 25
telnet <host address> 25 to connect
and issue appropriate commands

![WhatsApp Image 2024-04-16 at 09 14 34_98cb91aa](https://github.com/chandrumathiyazhagan/Enumeration/assets/119393023/fa644abb-e834-4078-abaa-df18d0f58e25)

## nmap –script smtp-enum-users.nse <hostname>
![6](https://github.com/chandrumathiyazhagan/Enumeration/assets/119393023/506a23a8-fd77-4031-986a-89e74b0f90f0)

## RESULT:
The Google hacking keywords and enumeration tools were identified and executed successfully
