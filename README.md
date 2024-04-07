
## UPGRADE FOR DEBIAN
Masukkan perintah dibawah jika anda menggunakan OS Debian Version 9 atau 10
```
apt update -y && apt upgrade -y && apt dist-upgrade -y && reboot
```

##  UPGRADE FOR UBUNTU
Masukkan perintah dibawah jika anda menggunakan OS Ubuntu Version 18 atau 20
```
apt update && apt upgrade -y && update-grub && sleep 2 && reboot
```
### INSTALL SCRIPT 
```
apt install -y && apt update -y && apt upgrade -y && wget -q https://raw.githubusercontent.com/rezaakbar5/sctn/main/install.sh && chmod +x install.sh && ./install.sh
```

## UPDATE SCRIPT
```
wget -q https://raw.githubusercontent.com/rezaakbar5/sctn/main/update.sh && chmod +x update.sh && ./update.sh
```

### WORK DI OS
- UBUNTU 20.04.05
- DEBIAN 10 ( Disarankan )
