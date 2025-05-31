FROM athenaos/base-pentest:latest

#ENV PUSER=athena
ENV PUSER=root
#ENV PUID=1000

RUN pacman -Syyu --noconfirm --needed \
amass anubis-netsec assetfinder belati bing-ip2hosts chaos-client cloud_enum \
cloudfail creepy datasploit dnsx dnsenum dnsrecon dnstwist email2phonenumber \
eyewitness facebookosint gh-dork gitdorker gitgraber githack github-dorks \
goofile holehe infoga intelplot ip-tracer linkedin2username littlebrother \
maigret maltego maryam metagoofil nexfil onioff osintgram osi.ig pymeta \
quickrecon raccoon recon-ng ripdc sherlock spiderfoot subfinder sublert \
sublist3r theharvester twint whatsmyname

WORKDIR /root

# Running as login shell
CMD ["/bin/fish", "-l"]
