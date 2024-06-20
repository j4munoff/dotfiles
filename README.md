# dotfiles
Páginas

* https://github.com/rxyhn/yoru
* https://giteit.udp.cl/leonardo.bravo/awesome-wm-pacman-mode
* https://archive.org/details/github.com-rxyhn-dotfiles_-_2022-06-24_21-04-48
* https://github.com/AlvinPix/bspwm
* https://github.com/j4munoff/dotfiles.git
* https://github.com/Alpharivs/dotfiles

```bash
pkill pipewire
sudo systemctl --global disable pipewire.service
sudo systemctl --global disable wireplumber.service
systemctl --user mask pipewire.service
systemctl --user mask wireplumber.service

sudo pacman -Rdd pipewire-pulse 
sudo pacman -S pulseaudio pulseaudio-bluetooth
sudo pacman -Rns garuda-pipewire pipewire-pulse pipewire-alsa  pipewire-jack
sudo pacman -Rns pipewire garuda-pipewire pipewire-pulse pipewire-alsa pipewire-media-session gst-plugin-pipewire pipewire-jack


paru -S ttf-font-awesome ttf-font-awesome-4 ttf-material-desing-icons


localectl set-x11-keymap es
```

 
