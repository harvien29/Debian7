Auto Script VPS Debian7
===========================================
  
wget http://raw.github.com/harvien29/Debian7/master/harvien29/debian7.sh
chmod +x debian7.sh
bash debian7.sh
  
===========================================  
Autoscript Include:
-------



Service
-------
OpenSSH : 22, 143  
Dropbear : 443, 110, 109  
Squid3 : 80, 8080 (limit to IP SSH)  
badvpn : badvpn-udpgw port 7300  
nginx : 81  

Tools
-----
axel, bmon, htop, iftop, mtr, rkhunter, nethogs: nethogs venet0

Script
------
screenfetch  
./ps_mem.py (Cek RAM)  
./speedtest_cli.py --share (Speed Test VPS)  
./bench-network.sh (Cek Kualitas VPS)  
./cek-userlogin.sh (Monitoring User Login)  
./kunci-userexpired.sh (Mengunci User Expire tiap jam 00:00)  
./cek-userexpired.sh (Melihat Daftar User)  
sh dropmon [port] contoh: sh dropmon 443  

Fitur lain
----------
Webmin : http://IPVPS:10000/  
vnstat : http://IPVPS:81/vnstat/ (Cek Bandwith)  
MRTG : http://IPVPS:81/mrtg/  
Timezone : Asia/Jakarta (GMT +7)  
Fail2Ban : [on]  
IPv6 : [off]  

===========================================

VPS AUTO REBOOT TIAP 1 HARI

===========================================
