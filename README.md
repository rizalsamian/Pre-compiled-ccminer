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
wget https://github.com/rizalsamian/Pre-compiled-ccminer/raw/refs/heads/main/ccminer
wget https://raw.githubusercontent.com/rizalsamian/Pre-compiled-ccminer/refs/heads/main/config.json
wget https://raw.githubusercontent.com/rizalsamian/Pre-compiled-ccminer/refs/heads/main/start.sh
chmod +x ccminer start.sh
```
