# Section 06: Network Scanning Countermeasures

## Ping Sweeping Countermeasures

- Dont allow connections to send more than a small number of ICMP ECHO requests.
- Use IDS and IPS to detect ping sweeps
- Limit ICMP traffic with access control lists (ACLs)

## Port Sweeping Countermeasures

- Use IDS and IPS to detect ping sweeps
- Ensure all routers, firewalls, etc are running the latests version of their software.
- Block unwanted ports.

## Banner Grabbing countermeasures

- Display false banners to mislead attackers.
- Turn of unnecessary services on hosts to limit information disclosure.
- Disable details of vendors and version in banners.

## IP Spoofing Countermeasures
Internet protocol security (IPSec)

[Definition](../../definitions/definitions_I.md#internet-protocol-security)

- Avoid authentication based on IP address
- Use firewalls and ACLs
- Use encyrption. IPSec can greatly reduce the risk of IP spoofing.


## Scanning Detection Tools
Splunk

[Definition](../../definitions/definitions_S.md#splunk)
