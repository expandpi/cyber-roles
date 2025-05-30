FROM athenaos/base-pentest:latest

#ENV PUSER=athena
ENV PUSER=root
#ENV PUID=1000

RUN pacman -Syyu --noconfirm --needed \
brutespray bruteforce-luks bruteforce-salted-openssl cewl cupp duplicut \
fern-wifi-cracker flask-unsign gpp-decrypt hash-extender hash-identifier \
hashid hashcat hashpump john johnny jwt-hack jwt-tool kerberoast kerbrute \
kekeo mimikatz patator pipal pyrit pwdump rcracki-mt samdump2 \
wpa2-halfhandshake-crack

WORKDIR /root

# Running as login shell
CMD ["/bin/fish", "-l"]
