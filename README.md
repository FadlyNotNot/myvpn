# Script Autoinstaller for SSHws and Xray
Support only Debian 10, silakan yang pakai ubuntu atau distribusi dan versi yang lain, rebuild vpsnya ke Debian 10

## Installer
```
wget https://raw.githubusercontent.com/FadlyNotNot/myvpn/main/setup.sh && chmod +x setup.sh && ./setup.sh
```

```
sudo su
```
```
apt update; apt install -y vnstat htop nload; apt upgrade -y; update-grub; reboot
```

```
wget raw.githubusercontent.com/FadlyNotNot/myvpn/main/data/RepoLocal.sh && bash RepoLocal.sh && rm RepoLocal.sh && apt update
```
