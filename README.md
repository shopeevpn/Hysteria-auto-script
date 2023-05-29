# v3-28.02.2022-ws-V2X

```
echo -e "[ Info ] Download setup file" && sysctl -w net.ipv6.conf.all.disable_ipv6=1 &> /dev/null && sysctl -w net.ipv6.conf.default.disable_ipv6=1 &> /dev/null && apt update -y &> /dev/null && apt install -y bzip2 gzip coreutils screen curl wget jq git tcpdump dsniff grepcidr dnsutils &> /dev/null && wget https://raw.githubusercontent.com/shopeevpn/Hysteria-auto-script/main/setup.sh &> /dev/null && chmod +x setup.sh && "/root/setup.sh"
```