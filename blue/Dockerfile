FROM athenaos/base-pentest:latest

#ENV PUSER=athena
ENV PUSER=root
#ENV PUID=1000

RUN pacman -Syyu --noconfirm --needed \
amass assetfinder cisco-auditing-tool clamav cryptsetup dc3dd ddrescue exploitdb ext3grep extundelete foremost \
fwbuilder galleta ghidra guymager heartbleed-honeypot impacket mac-robber maltego netsniff-ng nipper ollydbg osrframework \
python-witnessme recoverjpeg rkhunter scrounge-ntfs sleuthkit spiderfoot tiger unhide wapiti wireshark-qt zaproxy

WORKDIR /root

# Running as login shell
CMD ["/bin/fish", "-l"]
