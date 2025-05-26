# NMAP:- USED FOR ACTIVE RECONNAISSANCE WHICH INCLUDES VULNERABILITY SCANNING AND NETWORK MAPPING


# FOR HOST AND PORT SCANNING
1. firstly scan nmap subnet  with local ip to check which  host is up or down
       nmap -sn 127.0.0.1/8
2. default scan to 1000 ports
       nmap 127.0.0.1
3. scan for all 65535 ports
       nmap -p- 127.0.0.1
4. scan for specific ports 80-http 443-https
       nmap -p 80,443 127.0.0.1
# FOR SERVICE SCANNING
5. scan which service/version running is the open ports
       nmap -sV 127.0.0.1
# FOR OS DETECTION
6. it scan which os is currently used and version of it
        sudo nmap -O 127.0.0.1
