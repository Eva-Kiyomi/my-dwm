![Preview](screenshots/preview.png)
# Dependencies

### Fonts
- JetBrains Mono Nerd Font

### Build Tools
- make
- libx11-dev
- libxft-dev
- libxinerama-dev
- libxext-dev
    
### Audio (if you will use if)
- pulseaudio

### Brightness control
- brightnessctl
    
# Installation
```
sudo make clean install
```
# Run

```
exec dwm
```
# Configuring

Actual config is:  
```config.h```

# Create Desktop Entry

Entry path: 
```
/usr/share/xsessions/dwm.desktop
```
Entry content:
```
[Desktop Entry]
Encoding=UTF-8
Name=dwm
Comment=Dynamic window manager
Exec=dwm
Icon=dwm
Type=XSession
```

