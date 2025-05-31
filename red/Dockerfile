FROM athenaos/base-pentest:latest

#ENV PUSER=athena
ENV PUSER=root
#ENV PUID=1000

RUN pacman -Syyu --noconfirm --needed \
amass aquatone assetfinder aws-iam-privesc bloodhound brutespray burpsuite \
cewl chisel cloud_enum crackmapexec cupp dirb dirsearch dnscan dnsenum \
dnsrecon dnstwist dnsx evil-winrm ffuf feroxbuster findomain fierce gobuster \
httpx impacket-ba interlace johnny jwt-tool kerbrute ldapdomaindump legion \
linenum linux-exploit-suggester maltego masscan metasploit mimikatz \
mimipenguin netexec nmap nuclei o365enum osintgram photon proxychains-ng \
pwncat-caleb raccoon recon-ng responder smbmap snmpcheck smbclient smbexec \
snmpenum smbrelay spiderfoot spray365 sqlmap sshtrix sslscan subfinder \
sublist3r subjack theharvester vulmap webscarab websploit wfuzz whatweb \
wifite xsssniper xsstrike zaproxy zeek zizzania

WORKDIR /root

# Running as login shell
CMD ["/bin/fish", "-l"]
