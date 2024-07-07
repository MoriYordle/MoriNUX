#   MoriNUX KDE
Base:              - Arch Linux

Kernel:            - Linux

Shell:             - zsh

DE:                - Budgie

#   Appearance


**Style**:
      Widgets:                Fluent Round Dark Compact
      Icons:                  Tela Dark
      Cursors:                BreezeX Light
      Notification Possition: Bottom Right
      Dark Theme:             true
      Built-in Theme:         false
      Animations:             true
**Desktop**:
      Desktop Icons:          false
        Active Mounts:          false
        Home Directory:         false
        Trash:                  false
      Click Policy:           Double
      Icon Size:              Normal
      Number of Virtual Desktops: 2

**Fonts**:
    
    Window Titles:    Cantarell Bold        11pt
    
    Documents:        Cantarell Regular     11pt
    
    Interface:        Cantarell Regular     11pt
    
    Monospace:        Hurmit Nerd Font mono 10pt
    
    Text scaling:     1.00
    
    Hinting:          Slight

    Antialiasing:     Subpixel (for LCD screens)

**Raven**:
    - Calendar
    - Media Controls 
    - Usage Monitor
    - Sound Output
    - Sound Input
          Raven Position:        Right
          Notification order:    Newest to oldest
    
**Shell**:              ohmyzsh! "bira"
   - Install:
```
sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```

#   Applications

Web Browser:        Firefox

Files:              Nautilus

Email Client:       

Calendar:           Gnome Calendar

Music:              Rhythmbox

Video:              mpv

Photos:             Shotwell

#               Build

#   Paru
```
    - git clone https://aur.archlinux.org/paru-bin.git
    - cd paru-bin/
    - makepkg -si

paru -Sy --needed alacritty mpv gimp audacity steam libreoffice-still wine winetricks zsh nano fastfetch btop \
element-desktop godot qbittorrent dino git prismlauncher-bin blender-3.6-bin flatpak noto-fonts noto-fonts-cjk \
noto-fonts-emoji noto-fonts-extra pipewire-alsa pipewire-jack jdk8-openjdk linux-headers dosfstools xfsprogs unrar\
nkinitcpio-firmware ttf-material-design-icons-extended ttf-ms-win11-auto vesktop-bin classicube-git libcurl4 \
libopenal1 ozu-lazer-bin spotube-bin wireplumber qemu-full gnome-font-viewer shotwell file-roller gedit hexchat \
rhythmbox nautilus gnome-calendar
paru -R mate-terminal 
```

#   flatpak
```
flatpak install com.obsproject.Studio com.usebottles.bottles org.pitivi.Pitivi
```
