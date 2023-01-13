# Cenminmod Advanced 

CentminMod Config
```bash
mkdir -p /etc/centminmod 
wget https://raw.githubusercontent.com/bibicadotnet/cenminmod-bibica/main/custom_config.inc -O /etc/centminmod/custom_config.inc
```
Cài đặt CentminMod sử dụng PHP 8.0
```bash
yum -y update; curl -O https://centminmod.com/betainstaller80.sh && chmod 0700 betainstaller80.sh && bash betainstaller80.sh
```
Cài đặt CentminMod sử dụng PHP 7.4
```bash
yum -y update; curl -O https://centminmod.com/betainstaller74.sh && chmod 0700 betainstaller74.sh && bash betainstaller74.sh
```
