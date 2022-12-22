# SCMPORT - SSH / SSL / XRAY / DNSTT / OPENVPN V.1.0
- AUTOSCRIPT VPN

# UPDATE
<pre><code>apt-get update && apt-get upgrade -y && update-grub && sleep 2 && reboot</code></pre>

# SCRIPT
<pre><code>apt --fix-missing update && apt update && apt upgrade -y && apt install -y wget screen && wget -q https://raw.githubusercontent.com/SSHSEDANG4/multiws/main/setup.sh && chmod +x setup.sh && screen -S setup ./setup.sh</code></pre>

# SERVICE
[![Hits](https://img.shields.io/badge/SSH-WEBSOCKET-RED?style=for-the-badge&logo=cloudflare)](https://github.com/SSHSEDANG4)
[![Hits](https://img.shields.io/badge/SSH-SLOWDNS-RED?style=for-the-badge&logo=amazondynamodb)](https://github.com/SSHSEDANG4)
[![Hits](https://img.shields.io/badge/XRAY-WEBSOCKET-RED?style=for-the-badge&logo=cloudflare)](https://github.com/SSHSEDANG4)
[![Hits](https://img.shields.io/badge/XRAY-GRPC-RED?style=for-the-badge&logo=cloudflare)](https://github.com/SSHSEDANG4)
[![Hits](https://img.shields.io/badge/MULTI-PORT-RED?style=for-the-badge&logo=amazonec2)](https://github.com/SSHSEDANG4)

# TESTED ON OS 
- DEBIAN 10 & UBUNTU 20

# PORT INFO

|        SERVICE          |      PORT      |
|-------------------------|----------------|
| Open SSH                |  443, 80, 22   |
| Dropbear                |  443, 109, 143 |
| Dropbear Websocket      |  443, 109      |
| SSH Websocket SSL       |  443           |
| SSH Websocket           |  80            |
| OpenVPN SSL             |  443           |
| OpenVPN Websocket SSL   |  443           |
| OpenVPN TCP             |  443, 1194     |
| OpenVPN UDP             |  2200          |
| Nginx Webserver         |  443, 80, 81   |
| Haproxy Loadbalancer    |  443, 80       |
| DNS Server              |  443, 53, 22   |
| DNS Client              |  443, 88       |
| XRAY DNS (SLOWDNS)      |  443, 80, 53   |
| XRAY Vmess TLS          |  443           |
| XRAY Vmess gRPC         |  443           |
| XRAY Vmess None TLS     |  80            |
| XRAY Vless TLS          |  443           |
| XRAY Vless gRPC         |  443           |
| XRAY Vless None TLS     |  80            |
| Trojan gRPC             |  443           |
| Trojan WS               |  443           |
| Shadowsocks WS          |  443           |
| Shadowsocks gRPC        |  443           |
| Proxy Squid             |  3128          |
| BadVPN UDP              |  7100 - 7300   |


# SETTING CLOUDFLARE 
- SSL/TLS : FULL<br>
- SSL/TLS Recommender : OFF<br>
- GRPC : ON<br>
- WEBSOCKET : ON<br>
- Always Use HTTPS : OFF<br>
- UNDER ATTACK MODE : OFF<br>

# Server Features :
- Multi Path & Support Dynamic Path
- XrayDNS 2022
- Timezone Asia/Jakarta (GMT +7)
- Autoreboot On 05:00 GMT +7 
- Auto Delete Expired Account 
- Fully automatic script 
- Admin Control  
- Backup Data & Restore Data
- Fully automatic script 
- Full Orders For Various Services  
- Link Account Crate Protocol
- Format OpenClash

# REQUEST ACCESS 
- https://t.me/sshsedang
