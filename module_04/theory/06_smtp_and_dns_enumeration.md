# Section 06: SMTP and DNS enumeration

## SMTP
Simple mail transfer protocol (SMTP)

[Definition](../../definitions/definitions_S.md#simple-mail-transfer-protocol)

Post office protocol (POP)

[Definition](../../definitions/definitions_P.md#post-office-protocol)

nmap

[Definition](../../definitions/definitions_N.md#nmap)

`smtp-enum-users` (nmap)

Attempts to enumerate the users on a SMTP server by issuing the VRFY, EXPN or RCPT TO commands.
The goal of this script is to discover all the user accounts in the remote system.

Dig

[Definition](../../definitions/definitions_D.md#dig)

Nslookup

[Definition](../../definitions/definitions_N.md#nslookup)

DNS security extensions (DNSSEC)

[Definition](../../definitions/definitions_D.md#domain-name-system-security-extensions)

`broadcast-dns-service-discovery` (nmap)

Attempts to discover hosts' services using the DNS Service Discovery protocol.
It sends a multicast DNS-SD query and collects all the responses.

Links
- [https://nmap.org/nsedoc/scripts/smtp-enum-users.html](https://nmap.org/nsedoc/scripts/smtp-enum-users.html)
- [https://nmap.org/nsedoc/scripts/broadcast-dns-service-discovery.html](https://nmap.org/nsedoc/scripts/broadcast-dns-service-discovery.html)
