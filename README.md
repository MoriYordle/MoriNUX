#   MoriNUX
Base:               Arch Linux
Kernel:             Linux
Shell:              zsh

#    KDE Plasma    #

#   Appearance
App Style:          Breeze
App Style GTK:      Breeze
Plasma Style:       Fluent
Colors:             Catppuccin Mocha Mauve
Window decorations: Alba P6
Fonts:
    General:        Noto-sans             10pt
    Fixed Width:    Hurmit Nerd Font Mono 10pt
    Small:          Noto-sans             8pt
    Toolbar:        Noto-sans             10pt
    Menu            Noto-sans             10pt
    Window Title:   Noto-sans             10pt
Icons:              Tela Dark
Cursors:            Breeze Light
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
sudo pacman -Sy --needed alacritty kdenlive kmail kdeconnect okular gwenview spectacle elisa mpv flatpak gimp discord audacity steam libreoffice-still git noto-fonts noto-fonts-cjk noto-fonts-emoji noto-fonts-extra pipewire-alsa pipewire-jack jdk8-openjdk base-devel wine winetricks zsh nano fastfetch btop element-desktop dino linux-headers partitionmanager dosfstools
```

#   paru
# - Install Paru
```
    - git clone https://aur.archlinux.org/paru-bin.git
    - cd paru-bin/
    - makepkg -si

paru -Sy --needed mkinitcpio-firmware prismlauncher-qt5-bin blender-3.6-bin ttf-material-design-icons-extended ttf-ms-win11-auto ytdownloader-gui-bin
```

#   flatpak
```
flatpak install com.obsproject.Studio
```

#    XFCE    #

#    Appearance
Global Style:          Catppuccin Mocha Standard Mauve Dark
XFWM Styke:            Tgc
Fonts:
    General:        Noto-sans             10pt
    Fixed Width:    Hurmit Nerd Font Mono 10pt
    Small:          Noto-sans             8pt
    Toolbar:        Noto-sans             10pt
    Menu            Noto-sans             10pt
    Window Title:   Noto-sans             10pt
Icons:              Tela Dark
Cursors:            Breeze
Shell:              ohmyzsh! "bira"
    Install:            
```
sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```

#    Apps
# - paru
```
    - git clone https://aur.archlinux.org/paru-bin.git
    - cd paru-bin/
    - makepkg -si
paru -Sy --needed alacritty mpv gimp discord audacity steam libreoffice-still wine winetricks zsh nano fastfetch btop element-desktop \
dino git prismlauncher-qt5-bin blender-3.6-bin kdenlive okular partitionmanager flatpak noto-fonts noto-fonts-cjk \
noto-fonts-emoji noto-fonts-extra pipewire-alsa pipewire-jack jdk8-openjdk base-devel linux-headers \
dosfstools mkinitcpio-firmware ttf-material-design-icons-extended ttf-ms-win11-auto
paru -Syu
```

#   flatpak
```
flatpak install com.obsproject.Studio
```
