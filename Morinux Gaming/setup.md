#   MoriNUX KDE
Base:              - Arch Linux

Kernel:            - Linux Zen

Shell:             - zsh

DE:                - Budgie

#   Appearance

**Style**:
      Widgets:                Sweet Dark V40
      Icons:                  Miya Black
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
      Number of Virtual Desktops: 1

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

Files:              Nemo

Email Client:       

Calendar:           Gnome Calendar

Music:              Music

Video:              Clapper

Photos:             Loupe

#               Build

#   Paru
```
    - git clone https://aur.archlinux.org/paru-bin.git
    - cd paru-bin/
    - makepkg -si

paru -Sy --needed alacritty zsh nano fastfetch btop git blender-3.6-bin flatpak noto-fonts noto-fonts-cjk \
noto-fonts-emoji noto-fonts-extra pipewire-alsa pipewire-jack jdk8-openjdk linux-zen-headers dosfstools xfsprogs \
unrar nkinitcpio-firmware ttf-material-design-icons-extended ttf-ms-win11-auto classicube-git libcurl4 \
libopenal1 wireplumber file-roller ntfs-3g exfat-utils grub-customizer lightdm-settings gparted
paru -R mate-terminal 
```

#   flatpak
```
flatpak install flathub com.obsproject.Studio com.usebottles.bottles com.github.rafostar.Clapper org.gnome.Boxes \
org.gimp.GIMP org.audacityteam.Audacity com.valvesoftware.Steam org.libreoffice.LibreOffice im.riot.Riot \
org.qbittorrent.qBittorrent im.dino.Dino org.prismlauncher.PrismLauncher dev.vencord.Vesktop sh.ppy.osu \
com.github.KRTirtho.Spotube org.gnome.font-viewer org.gnome.Loupe org.gnome.TextEditor com.chatterino.chatterino \
org.gnome.Calendar io.bassi.Amberol com.github.tchx84.Flatseal org.gnome.Calculator org.gnome.clocks \
io.github.antimicrox.antimicrox page.kramo.Cartridges org.mozilla.Thunderbird sh.ppy.osu 
```
