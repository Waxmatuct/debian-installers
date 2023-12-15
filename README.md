# debian-installers

These are shortcuts in installing desktop environments and the BSPWM windows manager for Debian Stable.
XFCE and Budgie is vanilla out of the box desktop environment.
Plus BSPWM.
New to the repo is Budgie using Debian Stable with Debian Sid kernel PLUS other stuff.
If you use these for Debian Testing. It may work or ....

## Установка bspwm

```
sudo apt update && sudo apt upgrade -y
sudo apt install git micro exa nala xdg-user-dirs openssh-server

LC_ALL=en_US xdg-user-dirs-update --force

cd Downloads && git clone https://github.com/Waxmatuct/debian-installers.git && cd debian-installers
mv ~/.bashrc ~/.bashrc.bak
cp ./.bashrc ~/

./bspwm.sh
```
