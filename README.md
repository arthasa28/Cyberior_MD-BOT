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
deb http://ap-southeast-1.ec2.archive.ubu... focal main restricted universe multiverse
deb http://ap-southeast-1.ec2.archive.ubu... focal-updates main restricted universe multiverse
deb http://ap-southeast-1.ec2.archive.ubu... focal-security main restricted universe multiverse
deb http://ap-southeast-1.ec2.archive.ubu... focal-backports main restricted universe multiverse
deb http://ap-southeast-1.ec2.archive.ubu... focal-proposed main restricted universe multiverse
```
Update & Upgrade Repo
```bash
sudo apt update -y && apt upgrade -y
```
Install Plugin
```bash
sudo apt install unzip zip webp ffmpeg imagemagick git -y
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
unzip Cyberior-MD_BETA.zip
```
Masuk Ke Directory Cyberior-MD_BETA
```bash
cd Cyberior-MD_BETA
```
Install Module NODEJS di Directory Cyberior-MD_BETA
```bash
npm i
```
Jalankan BOT
```bash
npm start
```

## Donate
- [Saweria](https://saweria.co/arthasyarif)


# Official Group
- [Group](##)

