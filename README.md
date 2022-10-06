# Lab-1 : Reconnaisance
In this lab, you are going to do reconnaissance on the Boise State University using a variety of publicly available websites or open source software tools. Please upload a word document or pdf file that contains your answers.



## **Whois**

The **WHOIS** system allows access to directory information stored by domain name registrars.

Using whois (in your Kali VM), find information on the domain name "boisestate.edu" and answer the following questions

Command to run in Kali:
```
$ whois boisestate.edu
```
1. What is the email address associated with the technical contact for the domain name boisestate.edu?
2. What are the authoritative name servers for the domain boisestate.edu? (These are the name servers that provide the final official translation between the domain name boisestate.edu and its IP address)


## DNS

1. Using dnsdumpster.com obtain a list of sub domains for boisestate.edu and provide a list of 5 subdomains that you didn't know existed prior to running the scan. (Any 5 subdomains is fine,  screenshots are ok)
2. Upload the "Domain Map" image from DNS Dumpster that summarizes the search results for "boisestate.edu"
3. Use Fierce (in your Kali VM) to do a DNS scan:
     ```
     $ fierce --domain boisestate.edu
     ```
- What is the IP address for the host "gold.boisestate.edu"
- What is the IP address for the host "majors.boisestate.edu"


## SSL Certificates

SSL certificates can be a useful source of hostnames that may be of interest in a penetration test. You can inspect SSL certificates manually in your web browser.

Using  https://andrewmohawk.com/SSLAssociated/index.php search for boisestate.edu domain

What are the Alternate DNS Names?
