# Section 05: Scanning Beyond IDS and Firewall

## Evasion Techniques (Routing)
IDS (Intrusion detection system)

[Definition](../../definitions/definitions_I.md#intrusion-detection-system)

Techniques to evade IDS/firewalls are
- Proxy servers
- IP address spoofing
- Mac address spoofing
- Packet fragmentation

Packet fragmentation

[Definition](../../definitions/definitions_P.md#packet-fragmentation)

Source routing

[Definition](../../definitions/definitions_S.md#source-routing)

## Evasion Techniques (Spoofing)
Internet protocol (IP) address spoofing

[Definition](../../definitions/definitions_I.md#internet-protocol-address-spoofing)

Media access control (MAC) address spoofing

[Definition](../../definitions/definitions_M.md#media-access-control-address-spoofing)

## Evasion Techniques (Other)
Randomizing host order. The `nmap` option `--randomize-hosts` man pages is
```shell
--randomize-hosts (Randomize target host order)
   Tells Nmap to shuffle each group of up to 16384 hosts before it scans them. This can make the scans less obvious to various network monitoring systems, especially when
   you combine it with slow timing options. If you want to randomize over larger group sizes, increase PING_GROUP_SZ in nmap.h and recompile. An alternative solution is to
   generate the target IP list with a list scan (-sL -n -oN filename), randomize it with a Perl script, then provide the whole list to Nmap with -iL.
```

Proxy server

[Definition](../../definitions/definitions_P.md#proxy-server)