# dwm
mkdir .suckless
cd .suckless
git clone https://git.suckless.org/dwm
make alacritty your default terminal
git clone https://git.suckless.org/dmenu
make
sudo make clean install

If using display manager, create a dwm.desktop file in /usr/share/xsessions
