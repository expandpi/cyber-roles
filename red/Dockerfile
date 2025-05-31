FROM athenaos/base-pentest:latest

#ENV PUSER=athena
ENV PUSER=root
#ENV PUID=1000

RUN pacman -Syyu --noconfirm --needed \
amass aquatone assetfinder autovpn aws-iam-privesc bloodhound brutespray \
burpsuite cewl chisel cloud_enum crackmapexec crowbar cupp cyberscan dirb \
dirsearch dnscan dnsenum dnsrecon dnstwist dnsx evil-winrm eyewitness ffuf \
feroxbuster findomain fierce gobuster h8mail hakrawler httpx impacket-ba \
interlace johnny jwt-tool kerbrute ldapdomaindump legion linenum \
linux-exploit-suggester maltego masscan metasploit mimikatz mimipenguin naabu \
netexec nmap nuclei o365enum osintgram parameth patator photon proxychains-ng \
pwncat quickrecon raccoon recon-ng responder smbmap sn1per snmpcheck smbclient \
smbexec snmpenum smbrelay spiderfoot spray365 sqlmap sshtrix sslsplit sslscan \
subfinder sublist3r subjack theharvester trevorspray twint vulmap webanalyze \
webscarab websploit wfuzz whatweb wig wifite xerosploit xsssniper xsstrike zaproxy \
zeek zmap zgrab zizzania


WORKDIR /root

# Running as login shell
CMD ["/bin/fish", "-l"]
