# DNS, DHCP, and ARP

## DNS (Domain Name System)

### Theory
DNS converts domain names (like google.com)
into IP addresses so that systems can communicate.

### Basic Practical
Command:
nslookup google.com

Observation:
Returns the IP address associated with the domain.

### SOC Perspective
SOC analysts monitor DNS queries to detect
malicious domains, phishing, or command-and-control traffic.

---

## DHCP (Dynamic Host Configuration Protocol)

### Theory
DHCP automatically assigns IP addresses
to devices in a network.

### Basic Practical
Command:
ipconfig /all

Observation:
Shows DHCP server and assigned IP address.

### SOC Perspective
Unauthorized DHCP servers may indicate
rogue devices or network attacks.

---

## ARP (Address Resolution Protocol)

### Theory
ARP maps IP addresses to MAC addresses
within a local network.

### Basic Practical
Command:
arp -a

Observation:
Displays IP-to-MAC address mappings.

### SOC Perspective
ARP spoofing can be used for
man-in-the-middle attacks in local networks.
