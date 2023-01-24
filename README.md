# Simple Script Change to Root User (applies to all linux)


* First Step
```
sudo su && apt --fix-missing update -y && apt update && apt upgrade -y && apt install -y wget && apt install curl -y && update-grub
```
* Second Step
```
wget https://raw.githubusercontent.com/kurosewu/exroot/main/exroot.sh && bash exroot.sh
```
