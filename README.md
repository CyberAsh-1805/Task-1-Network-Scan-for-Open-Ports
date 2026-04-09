## Network Security Scan for open ports
- Tool used: Nmap + Wireshark
- Local ip range is 172.20.10.0/28
- Ip Address 1 (172.20.10.1)
open ports:-
21/tcp - ftp
53/tcp - Dns
49152/tcp - unknown 
62078/tcp - iphone sync
- Ip Address 2 (172.20.10.11)
open ports:-
135/tcp - msrpc 
139/tcp - netbios-ssn 
445/tcp - microsoft-ds (smb)
- Identified security risks
ftp- Transmits credentials in plaintext
Dns- vulnerable to Dns spoofing 
smb- Allows lateral movement in a network
