FROM athenaos/base-pentest:latest

#ENV PUSER=athena
ENV PUSER=root
#ENV PUID=1000

RUN pacman -Syyu --noconfirm --needed \
0d1n abuse-ssl-bypass-waf adminpagefinder ajpfuzzer albatar allthevhosts anti-xss \
apachetomcatscanner arachni arjun asp-audit bbqsql belati bfac bfuzz bing-lfi-rfi \
blisqy boofuzz brakeman brutexss bsqlbf bsqlinjector burpsuite cmsmap cmseek \
cmsscan cms-explorer commix corscanner corsy crlfuzz dalfox darkd0rk3r davscan \
detectem dirb dirbuster dirsearch dirstalk dotdotpwn droopescan drupalscan drupwn \
d-tect eyewitness feroxbuster ffuf filebuster filefuzz fimap fireprox flask-unsign \
fuxploider fuzzdb gau ghauri gitdump git-dumper gittools gobuster gospider \
gowitness graphqlmap graphw00f hakrawler httpx jaeles jexboss joomscan jwt-hack \
kadimus lfi-scanner lfimap lfisuite linkfinder log4j-scan lorsrf magescan nuclei \
parameth patator photon phpggc php-malware-finder phpsploit pixload portmanteau \
powerfuzzer qark ratproxy responder scanqli secretfinder shuffledns skipfish \
snallygaster sqlmap ssrfmap stunner subjs tplmap uniscan urlextractor v3n0m vega \
w3af wafw00f wapiti webscarab websploit wfuzz whatweb wig xsscrapy xsser xsstrike

WORKDIR /root

# Running as login shell
CMD ["/bin/fish", "-l"]
