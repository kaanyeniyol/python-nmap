# python-nmap

IP taramak istiyorsaniz   1:__
aginiza bagli ipler icin  2:__
ms17-010 taramasi icin    3:__
Zaafiyet taramasi icin    4:__


>>   ip adresinizi giriniz  : 192.168.100.166


Starting Nmap 7.70 ( https://nmap.org ) at 2018-12-13 17:57 T³rkiye Standart Saati
Pre-scan script results:
| broadcast-avahi-dos:
|   Discovered hosts:
|     224.0.0.251
|   After NULL UDP avahi packet DoS (CVE-2011-1002).
|   Hosts that seem down (vulnerable):
|_    224.0.0.251
Nmap scan report for 192.168.100.166
Host is up (0.0010s latency).

PORT    STATE SERVICE
445/tcp open  microsoft-ds

Host script results:
|_samba-vuln-cve-2012-1182: Could not negotiate a connection:SMB: Failed to receive bytes after 5 attempts: ERROR
|_smb-vuln-ms10-054: false
|_smb-vuln-ms10-061: Could not negotiate a connection:SMB: Failed to receive bytes after 5 attempts: ERROR

Nmap done: 1 IP address (1 host up) scanned in 57.18 seconds
