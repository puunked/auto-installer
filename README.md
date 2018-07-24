● Informações do script em destaque :

* OpenSSH, port : 22, 143
* Dropbear, port : 80, 444
* SSL/TLS SSH, port : 443
* Squid3, port : 8080, 3128 (limite para IP SSH)
* Badvpn : badvpn-udpgw port 7300
* Webmin : https://IPVPS:10000/
* Nginx : 81
* OpenVPN TCP 1194
* Script menu : para exibir o menu
* Script user-add : fazer uma conta SSH
* Script trial : criar uma conta trial
* Script user-del : excluir conta SSH
* Script user-login : conferir login usuario
* Script user-list : verificação usuario
* Script resvis : restart service dropbear, webmin, squid3, openvpn dan ssh
* Script speedtest : speedtest VPS
* Script about : informações sobre o script de instalação automática
* Antes do script de instalação automática seguinte ser instalado, verifique se o seu VPS tem OS Debian 8 32/64 Bit. Certifique-se de que o VPS ainda está vazia sem scripts anteriores.

● Copiar o seguinte comando e pressione enter
* apt-get install ca-certificates
* wget https://raw.githubusercontent.com/redeviver/auto-installer/master/debian.sh && chmod +x debian.sh && ./debian.sh
