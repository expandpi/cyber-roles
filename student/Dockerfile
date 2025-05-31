FROM athenaos/base-pentest:latest

#ENV PUSER=athena
ENV PUSER=root
#ENV PUID=1000

RUN pacman -Syyu --noconfirm --needed \
aircrack-ng binwalk burpsuite caido-desktop cewl commentor crunch dirb dirbuster dmitry \
edb enum4linux evil-winrm exploitdb fern-wifi-cracker ffuf fierce gobuster ghidra hashcat \
hydra john kismet legion medusa metasploit mimikatz mitmproxy nasm nikto nmap \
osert powersploit proxychains-ng pwncat-caleb python-hashid radare2 reaver responder \
rsmangler set spiderfoot spooftooph sqlmap theharvester unix-privesc-check villain \
wafw00f weevely wfuzz wifite wireshark-qt wordlister wpscan

WORKDIR /root

# Running as login shell
CMD ["/bin/fish", "-l"]
