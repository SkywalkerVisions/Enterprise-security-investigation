Enterprise Network Security & Access Control Investigation
WGU Cybersecurity Lab | November 2026 | Simulated educational environment
Overview- I explored how security controls protect different parts of an organization’s IT infrastructure. I examined Windows security settings, shared-folder access, Active Directory groups, network connections, and pfSense firewall configurations.

Tools and concepts- Windows, Windows Server, Active Directory, Group Policy, pfSense, traceroute, ARP, DNS, NAT, VPN routing, firewall rules, file permissions.

Investigations- Windows security and access. Reviewed sign-in settings, threat protection, and successful versus denied access to user and shared folders.

Network and firewall- Inspected ARP and forwarding tables, listening sockets, static routes, pfSense NAT and firewall rules, port forwarding, and DMZ rules.

Identity and authentication- Reviewed current-user identity, Active Directory Developers group membership, and Group Policy password settings.

Remote access- Used traceroute results to examine network paths and explored VPN split/full tunneling. The tunneling classification requires additional verification of the paths before publication.

Security recommendations- For a simulated credential-compromise scenario, recommended EDR, network segmentation, next-generation firewall/intrusion prevention, and phishing-resistant MFA. These were recommendations, not deployed controls.

SOC relevance- This lab developed my foundation in examining network behavior, reviewing security configurations, validating access restrictions, and documenting technical findings. It was not a production SOC investigation.

Evidence to add- (1) Sanitized screenshots of successful and denied shared- folder access (report p.3) (2) Sanitized pfSense firewall/NAT screenshots (report pp.6-7) (3) Sanitized Active Directory and Group Policy screenshots (report pp. 9-10) (4) Verified routing analysis with annotated traceroute evidence

Lessons learned- Firewalls, endpoint protection, network segmentation, and access controls each protect different parts of a system. Checking actual command results and permissions matters before drawing conclusions.
