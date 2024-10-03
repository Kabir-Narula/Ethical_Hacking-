
# Ethical Hacking Cheat Sheet

## Basics
### Attack Types
- **OS Attacks**: Targeting default OS settings.
- **App-Level Attacks**: Attacking vulnerabilities in application code.
- **Shrink Wrap Attacks**: Exploiting off-the-shelf scripts and code.
- **Misconfiguration Attacks**: Exploiting poorly configured systems.

---

## Penetration Testing Phases
1. **Reconnaissance**: Gathering initial information on the target.
2. **Scanning & Enumeration**: Identifying open ports and services.
3. **Gaining Access**: Exploiting vulnerabilities to enter systems.
4. **Maintaining Access**: Persisting access using backdoors.
5. **Covering Tracks**: Removing evidence of the breach.

---

## Legal References
- **18 U.S.C 1029 & 1030**: Fraud and related activity in connection with access devices.
- **RFC 1918**: Private IP standard.
- **SOX**: Corporate finance process regulations.
- **RFC 3227**: Guidelines for collecting and storing data.
- **GLBA**: Personal finance data protection.
- **ISO 27002**: Information Security Management.
- **FERPA**: Education records privacy.
- **CAN-SPAM**: Email marketing regulations.
- **FISMA**: Government network security standards.
- **SPY-Act**: License enforcement.
- **CVSS**: Common Vulnerability Scoring System.
- **DMCA**: Digital Millennium Copyright Act.
- **CVE**: Common Vulnerabilities and Exposure.

---

## Cryptography
### Symmetric Encryption
- **DES**: 56-bit key.
- **3DES**: 168-bit key.
- **AES**: 128, 192, or 256-bit key.
- **IDEA**: 128-bit key.
- **Twofish**: Up to 256-bit key.
- **Blowfish**: 64-bit block cipher.

### Asymmetric Encryption
- **Diffie-Hellman**: Key exchange algorithm.
- **ECC**: Elliptical Curve Cryptography, low power.
- **EI Gamal**: Encryption and digital signatures.
- **RSA**: Public key encryption, modern standard.

### Hash Algorithms
- **MD5**: 128-bit hash.
- **SHA1**: 160-bit hash.
- **SHA2**: 224, 256, 384, 512-bit variants.

### Trust Models
- **Web of Trust**: Entities sign certificates for each other.
- **Single Authority**: Central CA at the top.
- **Hierarchical**: CA at the top with RAs beneath.

---

## Reconnaissance
### Google Hacking Operators
- `site:`: Search within a specific site.
- `ext:`: Search by file extension.
- `intitle:`: Search for keywords in the title.
- `inurl:`: Search for keywords in the URL.
- `cache:`: Search within Google's cached version.

### DNS Record Types
- **A Record**: Maps IP to hostname.
- **MX Record**: Maps mail server.
- **CNAME**: Canonical name for an alias.
- **SOA**: Start of authority.
- **PTR**: Pointer for reverse DNS.
- **SRV**: Service record for host and port.

---

## Scanning & Enumeration
### Important Port Numbers
- **FTP**: 20, 21
- **SSH**: 22
- **Telnet**: 23
- **SMTP**: 25
- **DNS**: 53
- **HTTP**: 80, 8080
- **HTTPS**: 443
- **RDP**: 3389
- **SNMP**: 161/162

### ICMP Message Types
- **0**: Echo Reply
- **3**: Destination Unreachable
- **4**: Source Quench
- **5**: Redirect
- **8**: Echo Request
- **11**: Time Exceeded

### Nmap Scan Types
- `-sS`: SYN scan.
- `-sT`: TCP connect scan.
- `-sA`: ACK scan.
- `-sF`: FIN scan.
- `-sX`: Xmas scan.
- `-sN`: NULL scan.
- `-Pn`: No ping.

---

## Tools
### Vulnerability Research
- **National Vulnerability Database**
- **Exploit Database**

### Scanning Tools
- **Nmap**: Network mapping and scanning.
- **SuperScan**: Port scanning.
- **Netcat**: General-purpose network tool.
- **Hping**: Packet crafting and scanning.
- **NetScan Tools Pro**: Advanced network scanning.

### System Hacking Tools
- **Cain & Abel**: Password cracking.
- **John the Ripper**: Password brute force.
- **Hydra**: Password guessing.

### Sniffing Tools
- **Wireshark**: Packet capture and analysis.
- **tcpdump**: Command-line packet analysis.
- **Ettercap**: Network sniffing and MITM.

---

## Web-Based Hacking
### SQL Injection Types
- **Union Query**: Retrieve data using the `UNION` command.
- **Tautology**: Exploiting a true statement.
- **Blind SQL Injection**: No direct response from the server.
- **Error-Based SQL Injection**: Extracting data through error messages.

### HTTP Error Codes
- **200 Series**: OK responses.
- **400 Series**: Client errors.
- **500 Series**: Server errors.

### Cross-Site Request Forgery (CSRF)
- Forging requests to trick users into submitting malicious actions.

---

## Wireless Network Hacking
### Wireless Specifications
- **802.11a**: 30m range, 54 Mbps, 5 GHz.
- **802.11b**: 100m range, 11 Mbps, 2.4 GHz.
- **802.11g**: 100m range, 54 Mbps, 2.4 GHz.
- **802.11n**: 125m range, 100+ Mbps, 2.4/5 GHz.

### Bluetooth Attacks
- **Bluejacking**: Sending unsolicited messages.
- **Bluesnarfing**: Unauthorized access to data.
- **Bluesmacking**: Denial of Service.
- **Bluesniffing**: Bluetooth packet sniffing.

---

## Physical Security
### Categories of Security Measures
1. **Physical**: Cameras, locks, guards.
2. **Technical**: Smart cards, biometrics.
3. **Operational**: Policies and procedures.

---

## Social Engineering
### Human-Based Attacks
- **Impersonation**: Pretending to be a trusted entity.
- **Shoulder Surfing**: Observing screens or keyboards.
- **Tailgating**: Following someone into a restricted area.

### Computer-Based Attacks
- **Phishing**: Email scams.
- **Whaling**: Targeting executives.
- **Pharming**: Redirecting traffic to malicious websites.
