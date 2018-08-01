● Informações do script em destaque :

* OpenSSH, port : 22, 143
* Dropbear, port : 443, 444
* SSLH, port 443 : SSL/SSH Multiplexer
* SSL/TLS : 443
* STUNNEL : OVPN port : 587, SSH port : 943, DROPBEAR : 993, SQUID port : 8888  
* Squid3, port : 80, 3128, 8799, 8080 (limite para IP SSH)
* Badvpn : badvpn-udpgw port 7300
* Webmin : http://IPVPS:10000/
* Nginx : 81
* OpenVPN TCP 587
* OpenVPN TCP 1194 sslh
* OpenVPN TCP 1195 stunnel
* Script menu : para exibir o menu
* Script user-add : fazer uma conta SSH
* Script trial : criar uma conta trial
* Script user-del : excluir conta SSH
* Script user-login : conferir login usuario
* Script user-list : verificação usuario
* Script resvis : reiniciar serviços: dropbear, webmin, squid3, openvpn, sslh e ssh
* Script speedtest : speedtest VPS
* Script about : informações sobre o script de instalação automática
* Script VNC : Acesso via GUI : 5901
* Antes do script de instalação automática seguinte ser instalado, verifique se o seu VPS tem OS Debian 8 32/64 Bit. Certifique-se de que o VPS ainda está vazia sem scripts anteriores.

● Copiar o seguinte comando e pressione enter

* wget https://raw.githubusercontent.com/redeviver/auto-installer/master/debian.sh && chmod +x debian.sh && ./debian.sh
