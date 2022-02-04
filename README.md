<h2 align="center">
Auto Script Install All VPN Service
Mod SL
<img src="https://img.shields.io/badge/Version-1.0.0-blue.svg"></h2>

</p> 
<h2 align="center"> Supported Linux Distribution</h2>
<p align="center"><img src="https://d33wubrfki0l68.cloudfront.net/5911c43be3b1da526ed609e9c55783d9d0f6b066/9858b/assets/img/debian-ubuntu-hover.png"></p> 
<p align="center"><img src="https://img.shields.io/static/v1?style=for-the-badge&logo=debian&label=Debian%209&message=Stretch&color=red"> <img src="https://img.shields.io/static/v1?style=for-the-badge&logo=debian&label=Debian%2010&message=Buster&color=red">
<p align="center"><img src="https://img.shields.io/static/v1?style=for-the-badge&logo=ubuntu&label=Ubuntu%2018&message=Lts&color=red"> <img src="https://img.shields.io/static/v1?style=for-the-badge&logo=ubuntu&label=Ubuntu%2020&message=Lts&color=red">
</p>

<p align="center"><img src="https://img.shields.io/badge/Service-Websocket-success.svg">  
<p align="center"><img src="https://img.shields.io/badge/Service-OpenSSH-success.svg">  <img src="https://img.shields.io/badge/Service-Dropbear-success.svg">  <img src="https://img.shields.io/badge/Service-BadVPN-success.svg">  <img src="https://img.shields.io/badge/Service-Stunnel-success.svg">  <img src="https://img.shields.io/badge/Service-OpenVPN-success.svg">  <img src="https://img.shields.io/badge/Service-Squid3-success.svg">  <img   src="https://img.shields.io/badge/Service-Webmin-success.svg">  <img src="https://img.shields.io/badge/Service-SlowDns-success.svg">   <img
src="https://img.shields.io/badge/Service-Xray-success.svg">  <img src= "https://img.shields.io/badge/Service-SSR-success.svg">  <img src="https://img.shields.io/badge/Service-Trojan-success.svg">  <img src="https://img.shields.io/badge/Service-WireGuard-success.svg">  <img src= "https://img.shields.io/badge/Service-Shadowsocks-success.svg">  

## Commands : <img src="https://img.shields.io/static/v1?style=for-the-badge&logo=powershell&label=Shell&message=Bash%20Script&color=lightgray">

## Installation 

##   <img src="https://img.shields.io/badge/Service-Update%20Dulu-green"> 
  ```html
apt-get update && apt-get upgrade -y && update-grub && sleep 2 && reboot
```

##  <img src="https://img.shields.io/badge/Install Semua-VPN%20Batch-green">
  ```html
sysctl -w net.ipv6.conf.all.disable_ipv6=1 && sysctl -w net.ipv6.conf.default.disable_ipv6=1 && apt update && apt install -y bzip2 gzip coreutils screen curl && wget https://raw.githubusercontent.com/fisabiliyusri/test1/main/setup.sh && chmod +x setup.sh && sed -i -e 's/\r$//' setup.sh && screen -S setup ./setup.sh
```

##    <img src="https://img.shields.io/badge/Install%20Hanya-SSH%2FSSH%20SSL(Stunnel)%20SSH--Websocket%20Python%20BadVPN--UDPGW-green">
   ```html
sysctl -w net.ipv6.conf.all.disable_ipv6=1 && sysctl -w net.ipv6.conf.default.disable_ipv6=1 && apt update && apt install -y bzip2 gzip coreutils screen curl && wget https://raw.githubusercontent.com/fisabiliyusri/test1/main/install/sshonly.sh && chmod +x sshonly.sh && sed -i -e 's/\r$//' sshonly.sh && screen -S sshonly ./sshonly.sh
```

## About :
	       
       # Fork first , then change this .
       # Replace all this with your own acc name :
	     
	                    >  GitUser="fisabiliyusri" <
	              #wget https://github.com/${GitUser}/
	      


