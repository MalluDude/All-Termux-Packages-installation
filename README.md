
# AUTOMATICALLY INSTALLATION
#make sure that you already given termux storage permission..

```
termux-setup-storage

sleep 5

pkg update -y && pkg upgrade -y
pkg install git -y
pkg install bash -y

git clone https://github.com/MalluDude/All-Termux-Packages-installation.git

cd All-Termux-Packages-installation 

chmod +x *

bash install.sh
```
