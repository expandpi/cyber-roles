FROM athenaos/base-pentest:latest

#ENV PUSER=athena
ENV PUSER=root
#ENV PUID=1000

RUN pacman -Syyu --noconfirm --needed \
3proxy aiengine airgeddon airoscript arping-th bettercap captipper chisel dnschef \
dnsteal driftnet dshell eaphammer etherflood evillimiter fakenet-ng fern-wifi-cracker \
giskismet habu hostapd-wpe httpry impacket-ba intercepter-ng kismet linset macchanger \
mana massdns mitm6 mitmf mptcp-abuse mubeng nbname netdiscover netexec networkminer \
nmap obfs4proxy pcapxray peepdf proxmark proxychains-ng responder rfcat sniffjoke \
snort sparta sslsniff tcpdump wireshark-qt xplico zizzania

WORKDIR /root

# Running as login shell
CMD ["/bin/fish", "-l"]
