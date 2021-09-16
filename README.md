# scan_VictorG_ttlOS

Canal de youtube  https://youtube.com/c/Anonimo501

Grupo en Telegram https://t.me/Pen7esting

## scan_VictorG_ttlOS

Script de Escaneo TCP

Es necesario tener Go instalado en el equipo para que todo funcione correctamente como usuario root (sudo -i).

# Instalacion

apt install libpcap-dev golang -y

go get -u github.com/liamg/furious

wget -k https://cybexsec.es/scan.txt -O /bin/scan

chmod +x /bin/scan

# Uso

scan 127.0.0.1
