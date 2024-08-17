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

Web Browser:        Firefox

Email Client:       KMail

Dialer:             KDE Connect

File Manager:       Dolphin

File Archiver:      Ark

Terminal emulator:  Konsole

Text Editor:        Kate

Office:             LibreOffice

PDF:                Okular

Image Viewer:       GwenView

Music:              Elisa

Video:              MPV

Map:                Google Maps

#   Widgets
-PlasMusic
-Minimalist Clock

#               Build

#   Pacman
```
    - git clone https://aur.archlinux.org/paru-bin.git
    - cd paru-bin/
    - makepkg -si

paru -Sy --needed alacritty kdenlive kmail kdeconnect okular gwenview spectacle elisa mpv flatpak \
gimp audacity steam libreoffice-fresh git noto-fonts noto-fonts-cjk noto-fonts-emoji noto-fonts-extra \
pipewire-alsa pipewire-jack jdk8-openjdk base-devel zsh nano fastfetch btop element-desktop dino \
linux-zen-headers partitionmanager dosfstools mkinitcpio-firmware prismlauncher-bin blender-3.6-bin \
ttf-material-design-icons-extended ttf-ms-win11-auto ytdownloader-gui-bin spotube-bin ntfs-3g \
exfat-utils grub-customizer gst-libav gst-plugins-good gst-plugin-openh264 gnome-boxes
paru -R htop 
```

#   flatpak
```
flatpak install com.obsproject.Studio com.usebottles.bottles dev.vencord.Vesktop \
com.github.tchx84.Flatseal sh.ppy.osu
```
