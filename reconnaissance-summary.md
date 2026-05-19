# Active Reconnaissance Summary

## Objective
Perform active reconnaissance against the target systems to identify exposed services, open ports, and potential vulnerabilities.

## Activities Performed
- Conducted host discovery and network scanning using Nmap
- Enumerated open ports and running services
- Identified service versions and operating system information
- Performed basic web enumeration

## Key Findings
- Multiple ports were exposed to the internet
- Services such as HTTP, SMB, and RPC were identified
- Service version disclosure allowed fingerprinting of systems
- Some services appeared outdated and potentially vulnerable

## Security Impact
Exposed services increase the attack surface of the organization. Attackers can use service information to identify known vulnerabilities and launch targeted attacks.

## Recommendations
- Disable unnecessary services and ports
- Restrict external access using firewall rules
- Regularly patch and update exposed services
- Disable service version disclosure where possible
- Implement network monitoring and intrusion detection systems

## Conclusion
The reconnaissance phase successfully identified publicly exposed services and potential attack vectors that could be leveraged by attackers during later exploitation phases.
