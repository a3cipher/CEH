# Section 06: SMTP and DNS enumeration

## SMTP
SMTP (Simple mail transfer protocol)
> The Simple Mail Transfer Protocol (SMTP) is an Internet standard communication protocol for electronic mail transmission.

POP3
> In computing, the Post Office Protocol (POP) is an application-layer Internet standard protocol used by e-mail clients to retrieve e-mail from a mail server.
> POP version 3 (POP3) is the version in common use, and along with IMAP the most common protocols for email retrieval.

nmap
> Nmap is a network scanner created by Gordon Lyon.
> Nmap is used to discover hosts and services on a computer network by sending packets and analyzing the responses.
> Nmap provides a number of features for probing computer networks, including host discovery and service and operating system detection.

smtp-enum-users (nmap)
> Attempts to enumerate the users on a SMTP server by issuing the VRFY, EXPN or RCPT TO commands.
> The goal of this script is to discover all the user accounts in the remote system.

Dig
> Extensive web interface to dig for doing online dns lookup / nameserver query.

Nslookup
> nslookup is a network administration command-line tool for querying the Domain Name System to obtain the mapping between domain name and IP address, or other DNS records.

DNSSEC (DNS security extensions)
> The Domain Name System Security Extensions (DNSSEC) is a suite of extension specifications by the Internet Engineering Task Force (IETF) for securing data exchanged in the Domain Name System (DNS) in Internet Protocol (IP) networks.

broadcast-dns-service-discovery
> Attempts to discover hosts' services using the DNS Service Discovery protocol.
> It sends a multicast DNS-SD query and collects all the responses.

Links
- [https://en.wikipedia.org/wiki/Simple_Mail_Transfer_Protocol](https://en.wikipedia.org/wiki/Simple_Mail_Transfer_Protocol)
- [https://en.wikipedia.org/wiki/Post_Office_Protocol](https://en.wikipedia.org/wiki/Post_Office_Protocol)
- [https://nmap.org/nsedoc/scripts/smtp-enum-users.html](https://nmap.org/nsedoc/scripts/smtp-enum-users.html)
- [https://en.wikipedia.org/wiki/Domain_Name_System_Security_Extensions](https://en.wikipedia.org/wiki/Domain_Name_System_Security_Extensions)
- [https://nmap.org/nsedoc/scripts/broadcast-dns-service-discovery.html](https://nmap.org/nsedoc/scripts/broadcast-dns-service-discovery.html)
