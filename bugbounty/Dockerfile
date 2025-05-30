FROM athenaos/base-pentest:latest

#ENV PUSER=athena
ENV PUSER=root
#ENV PUID=1000

RUN pacman -Syyu --noconfirm --needed \
altdns arjun assetfinder awsbucketdump burpsuite caido-desktop changeme chaos-client commentor commix \
corsy corstest crlfuzz crunch dalfox depix dirb dirbuster-ng dirsearch dirstalk dnscan docem domained dotdotpwn \
dvcs-ripper eyewitness exploitdb extended-ssrf-search fdsploit feroxbuster ffuf filebuster findomain \
findsploit gau git-dumper gitgraber gitleaks gitminer gobuster gospider graphqlmap hakrawler hakrevdns \
httpx httpscreenshot hydra injectus jaeles joomscan jsonbee jwt-cracker jwt-hack knock linkfinder liffy \
lorsrf masscan massdns metasploit naabu nmap nikto nosqli nuclei parampampam patator phpggc psudohash \
rbndr rustscan s3scanner sandmap scrying second-order shhgit sleuthql sqlmap ssrf-sheriff \
ssrfmap subfinder subjack sublist3r subover trufflehog vhostscan wafw00f webanalyze whatweb \
wfuzz whispers wpscan wordlister xsscon xspear xsrfprobe xsser xsstrike xxeinjector xxeserv xxexploiter ysoserial

WORKDIR /root

# Running as login shell
CMD ["/bin/fish", "-l"]
