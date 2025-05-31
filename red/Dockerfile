FROM athenaos/base-pentest:latest

#ENV PUSER=athena
ENV PUSER=root
#ENV PUID=1000

RUN pacman -Syyu --noconfirm --needed \
amass aquatone assetfinder autovpn aws-iam-privesc bloodhound brutespray \
burpsuite cewl chisel cloud_enum crackmapexec crowbar cupp dirb \
dirsearch dnscan dnsenum dnsrecon dnstwist dnsx evil-winrm eyewitness ffuf \
feroxbuster findomain fierce gobuster httpx impacket-ba \
interlace johnny jwt-tool kerbrute ldapdomaindump legion linenum \
linux-exploit-suggester maltego masscan metasploit mimikatz mimipenguin \
netexec nmap nuclei o365enum osintgram patator photon proxychains-ng \
pwncat-caleb quickrecon raccoon recon-ng responder smbmap sn1per snmpcheck smbclient \
smbexec snmpenum smbrelay spiderfoot spray365 sqlmap sshtrix sslscan \
subfinder sublist3r subjack theharvester vulmap webscarab websploit wfuzz whatweb \
wifite xsssniper xsstrike zaproxy zeek zizzania


WORKDIR /root

# Running as login shell
CMD ["/bin/fish", "-l"]
