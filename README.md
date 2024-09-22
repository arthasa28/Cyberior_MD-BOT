## SC BOT WHATS APP

 	Extrack Terlebih dahulu File ZIPnya
-----------------------------------------------------

<p align="center">
<img src="https://github.com/zeeoneofficial/Haruka-Md/blob/v1/media/Haruka.jpg" alt="CYBERIR-MD" width="100"/>


## Install For VPS ( Linux, Ubuntu, Debian, Kali Linux )

Masuk Ke SUPER USER
```bash
sudo su
```
Edit File source.list
```bash
nano /etc/apt/source.list
```
Copy Lalu Paste di Source List, abis itu save, CTRL + X lalu y dan enter
```bash
deb http://ap-southeast-1.ec2.archive.ubuntu.com/ubuntu/ focal main restricted universe multiverse
deb http://ap-southeast-1.ec2.archive.ubuntu.com/ubuntu/ focal-updates main restricted universe multiverse
deb http://ap-southeast-1.ec2.archive.ubuntu.com/ubuntu/ focal-security main restricted universe multiverse
deb http://ap-southeast-1.ec2.archive.ubuntu.com/ubuntu/ focal-backports main restricted universe multiverse
deb http://ap-southeast-1.ec2.archive.ubuntu.com/ubuntu/ focal-proposed main restricted universe multiverse
```
Update & Upgrade Repo
```bash
sudo apt update -y && apt upgrade -y
```
Install Plugin
```bash
sudo apt install unzip zip webp mc yarn ffmpeg imagemagick git -y
```
Masuk ke folder Home ( Opsional )
```bash
cd /home
```
Download Nodejs Melalu Link
```bash
wget https://nodejs.org/dist/v20.11.1/node-v20.11.1-linux-x64.tar.xz
```
Extrack Nodejs
```bash
tar -xf node-v20.11.1-linux-x64.tar.xz
```
Pindahkan Folder node-v20.11.1-linux-x64 ke /opt
```bash
mv node-v20.11.1-linux-x64 /opt/
```
Edit file ~/.profile
```bash
nano ~/.profile
```
Tambahkan Isi ini ke dalam ~/.profile, Save CTRL + X dan y lalu enter
```bash
export NODEJS_HOME=/opt/node-v20.11.1-linux-x64/bin
export PATH=$NODEJS_HOME:$PATH
```
setelah Save, jangan lupa source file Fix.profile anda
```bash
source ~/.profile
```
Lalu Clone Repo Ke Folder Home ( VPS )
```bash
git clone https://github.com/arthasa28/Cyberior_MD-BOT
```
Masuk Ke Folder Cyberior_MD-BOT 
```bash
cd Cyberior_MD-BOT
```
Extract File Cyberior-MD_BETA.zip
```bash
unzip bot.zip
```
Masuk Ke Directory Cyberior-MD_BETA
```bash
cd bot
```
Install Module NODEJS di Directory Cyberior-MD_BETA
```bash
npm i
```
Jalankan BOT
```bash
npm start
```
</br>

## Menjalankan BOT Di Backround 24Jam FULL ON
Install Plugin di Folder BOTnya
```bash
npm install pm2 -g
```
Anda bisa menjalankan bot WhatsApp dengan PM2 agar berjalan nonstop.
```bash
pm2 start index.js
```
Untuk memastikan bot berjalan terus-menerus meski server reboot
```bash
pm2 startup
```
```bash
pm2 save
```

Menghentikan BOT 
```bash
pm2 stop index.js
```
</br>
<strong>Tambahan....</strong>

Untuk melihat status bot
```bash
pm2 status
```
Me-restart bot secara manual
```bash
pm2 restart index.js
```
Untuk Memonitoring Bot
```bash
pm2 logs
```

</br>

## Jika NPM & NODEJS sudah di install tapi di suruh install lagi, jalankan perintah di bawah ini
```bash
source ~/.profile
```



## Donate
- [Saweria](https://saweria.co/arthasyarif)


# Official Group
- [Group 🤑🤑](https://chat.whatsapp.com/HFz5GTte4Hv93xxZwAGds2)
- [Group VVIP🔥🔥](https://sfl.gl/Sx6YeqKgE2fp)

