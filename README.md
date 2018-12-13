# python-nmap

IP taramak istiyorsaniz   1:<br />
aginiza bagli ipler icin  2:<br />
ms17-010 taramasi icin    3:<br />
Zaafiyet taramasi icin    4:<br />


>>   ip adresinizi giriniz  : 192.168.100.166<br />


Starting Nmap 7.70 ( https://nmap.org ) at 2018-12-13 17:57 T³rkiye Standart Saati<br />
Pre-scan script results:<br />
| broadcast-avahi-dos:<br />
|   Discovered hosts:<br />
|     224.0.0.251<br />
|   After NULL UDP avahi packet DoS (CVE-2011-1002).<br />
|   Hosts that seem down (vulnerable):<br />
|_    224.0.0.251<br />
Nmap scan report for 192.168.100.166<br />
Host is up (0.0010s latency).<br />

PORT    STATE SERVICE<br />
445/tcp open  microsoft-ds<br />

Host script results:<br />
|_samba-vuln-cve-2012-1182: Could not negotiate a connection:SMB: Failed to receive bytes after 5 attempts: ERROR<br />
|_smb-vuln-ms10-054: false<br />
|_smb-vuln-ms10-061: Could not negotiate a connection:SMB: Failed to receive bytes after 5 attempts: ERROR<br />

Nmap done: 1 IP address (1 host up) scanned in 57.18 seconds<br />
