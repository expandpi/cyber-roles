FROM athenaos/base-pentest:latest

#ENV PUSER=athena
ENV PUSER=root
#ENV PUID=1000

RUN pacman -Syyu --noconfirm --needed \
aesfix aeskeyfind aespipe androidpincrack asleap bkcrack bruteforce-luks \
bruteforce-salted-openssl brutessh brutex brutespray cewl chapcrack \
crackpkcs12 creddump crowbar cupp eapmd5pass facebash fern-wifi-cracker \
findmyhash gpp-decrypt hash-buster hashcat hashid hash-identifier hashpump \
johnny keimpx kerbrute ldap-brute mimikatz mimipenguin ophcrack patator \
pemcrack phrasendrescher pip3line pkcrack pyrit rainbowcrack rcracki-mt \
samdump2 snmp-brute spray365 sshatter sucrack thc-pptp-bruter wifibroot \
wpforce xorsearch

WORKDIR /root

# Running as login shell
CMD ["/bin/fish", "-l"]
