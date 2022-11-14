# Section 03: Port and Service Discovery

## TCP Scanning
Scanning can be roughly divided into:
- Open TCP scanning
- Stealth TCP scanning
- UDP scanning
- SCTP scanning
- IPv6 scanning

## UDP Scan
UDP scan be done using `nmap` by running

```shell
nmap -sU 10.10.10.10
```

## Service Version Discovery
A port is assigned a service to run on, and every service has a specific version.

Version detection using `nmap`

```shell
nmap -sV
```

## nmap Reduction Techniques
### Method 1
Below we list several techniques for reducing `nmap` scanning time.
- Limit the number of ports (e.g. default 1000)
- Port scan (`-sn`) can be skipped if only liveness of hosts needs to be checked.
- Avoid advanced scan types (`--traceroute`)

### Method 2
Optimizing time parameters. Consider `-T` option for `nmap`
```shell
  -T<0-5>: Set timing template (higher is faster)
```

### Method 3
Separate TCP and UDP scanning into different scans.
