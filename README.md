# Autoscript VPS Debian 9
**Created by MYTH**

Server Information:
	+ Timezone : Asia/Kuala_Lumpur (GMT +8)
	+ IPtables : [ON]
	+ Fail2Ban : [ON]
	+ Auto-Reboot : [OFF]
	+ IPv6 : [OFF]

Service Installed:
	+ SSH : 22
	+ Dropbear : 442, 444
	+ Stunnel : 443
	+ Squid Proxy : 8080, 3128
	+ OpenVPN : TCP 1194, SSL 587
	+ BadVPN : 7300
	+ Nginx : 80
	+ Webmin : 10000

IMPORTANT:
	+ Webmin : http://$MYIP:10000/
	+ OpenVPN Config : http://$MYIP/Configs.zip

To display menu, type command `menu`.

INSTALLATION: `bash -c "$(wget https://git.io/JebpY -qO-)"`