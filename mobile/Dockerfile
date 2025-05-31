FROM athenaos/base-pentest:latest

#ENV PUSER=athena
ENV PUSER=root
#ENV PUID=1000

RUN pacman -Syyu --noconfirm --needed \
amoco androbugs androick android-apktool androidpincrack androidsniffer \
androwarn apkid apkleaks apkstat apkstudio apkurlgrep appmon backdoor-apk \
bagbak bandicoot binaryninja bytecode-viewer cafebabe dex2jar dnspy \
drozer edb frida-extract frida-ios-dump hookanalyser hopper ida-free idb \
iphoneanalyzer jeb-android jeb-arm jeb-intel jeb-mips lief \
malwareanalyser mobsf needle nili objection phoneinfoga phonesploit \
pyaxmlparser pyinstxtractor python-frida python-frida-tools qark \
quark-engine recaf stacoan triton vivisect

WORKDIR /root

# Running as login shell
CMD ["/bin/fish", "-l"]
