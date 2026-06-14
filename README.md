# Network Scanning & Enumeration using Nmap

## Objective

Perform network reconnaissance and service enumeration using Nmap to identify active hosts, open ports, running services, and potential attack surfaces.

## Tools Used

- Nmap
- Kali Linux

## Scan Types Performed

### Host Discovery (-sn)

Identified live hosts within the target network.

### SYN Scan (-sS)

Performed stealthy TCP SYN scanning to identify open ports.

### TCP Connect Scan (-sT)

Established full TCP connections to identify accessible services.

### Full Port Scan (-p-)

Scanned all 65535 TCP ports to identify exposed services.

### Service Detection (-sV)

Enumerated service versions running on discovered ports.

### OS Detection (-O)

Performed operating system fingerprinting.

### Aggressive Scan (-A)

Combined OS detection, version detection, NSE scripts, and traceroute.

### Default Script Scan (-sC)

Executed Nmap Scripting Engine default scripts.

### UDP Scan (-sU)

Identified open UDP services.

### NSE Script Scanning

Executed Nmap scripts to gather additional service information.

## Key Findings

- Active hosts identified
- Open TCP and UDP ports discovered
- Running services enumerated
- Operating system information identified
- Additional information gathered using NSE scripts

## Security Recommendations

- Disable unnecessary services
- Restrict exposed ports using firewalls
- Apply security updates regularly
- Monitor network services for unauthorized access

## Conclusion

Nmap successfully identified active hosts, open ports, running services, and operating system information, providing visibility into the network attack surface.
