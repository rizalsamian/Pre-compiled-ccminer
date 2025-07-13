# Instalation
1. Download dan Install Termux Apk
```
https://github.com/termux/termux-app/releases
```
2. Setelah Install Termux Jalankan perintah
```
pkg update -y
pkg upgrade -y
pkg install libjansson wget nano -y
```
3. Download CCMiner, Konfig, dan Jalankan
```
mkdir ccminer && cd ccminer
wget https://github.com/rizalsamian/Pre-compiled-ccminer/generic/ccminer
wget https://github.com/rizalsamian/Pre-compiled-ccminer/generic/config.json
wget https://github.com/rizalsamian/Pre-compiled-ccminer/generic/start.sh
chmod +x ccminer start.sh
```
