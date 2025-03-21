#   MoriNUX KDE
Base:              - Arch Linux

Kernel:            - Linux

Shell:             - zsh

DE:                - KDE Plasma

#   Appearance


App Style:          Breeze 

App Style GTK:      Breeze 

Plasma Style:       Fluent Round

Colors:             Catppuccin Mocha Mauve
```
git clone --depth=1 https://github.com/catppuccin/kde catppuccin-kde && cd catppuccin-kde
./install.sh
```

Window decorations: Alba P6 

Fonts:
    
    General:        Noto-sans             10pt
    
    Fixed Width:    Hurmit Nerd Font Mono 10pt (https://www.nerdfonts.com/font-downloads)
    
    Small:          Noto-sans             8pt
    
    Toolbar:        Noto-sans             10pt
    
    Menu            Noto-sans             10pt
    
    Window Title:   Noto-sans             10pt
    
Icons:              Tela Dark (https://store.kde.org/p/1279924)

Cursors:            BreezeX Light (https://store.kde.org/p/1640746)

System Sounds:      Ocean

Splashscreen:       Catppuccin Mocha Mauve

SDDM:               Catppuccin Mocha

Shell:              ohmyzsh! "bira"

   - Install:
```
sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```

#   Aplications

Web Browser:        Zen Browser

Email Client:       KMail

Dialer:             KDE Connect

File Manager:       Dolphin

File Archiver:      Ark

Terminal emulator:  Alacritty

Text Editor:        Kate

Office:             LibreOffice

PDF:                Okular

Image Viewer:       GwenView

Music:              AudioTube

Video:              MPV

Map:                Google Maps

#   Widgets
-PlasMusic
-Minimalist Clock
-Ginti
-Start next menu

#               Build

#   Pacman
```
    - git clone https://aur.archlinux.org/paru-bin.git
    - cd paru-bin/
    - makepkg -si

paru -Sy --needed alacritty btop curl element-desktop exfat-utils fastfetch ffmpeg flatpak gimp git gst-libav gst-plugin-pipewire gst-plugins-bad gst-plugins-bad-libs gst-plugins-base gst-plugins-base-libs gst-plugins-good gstreamer kalk kate kdeconnect kdenlive kvantum libreoffice-fresh libvirt linux-zen-headers lua libratbag mesa mesa-utils nano noto-fonts noto-fonts-cjk noto-fonts-emoji noto-fonts-extra ntfs-3g partitionmanager piper pipewire-alsa pipewire-jack pipewire-pulse prismlauncher-qt5-bin qemu steam tokodon ttf-ms-win11-auto ungoogled-chromium unrar unzip vesktop-bin virt-manager qbittorrent zen-browser-bin zsh

paru -R htop 
```

#   flatpak
```
flatpak install flathub com.github.tchx84.Flatseal com.usebottles.bottles
```
