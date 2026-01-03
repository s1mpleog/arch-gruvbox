# Arch Gruvbox Rice

My personal Gruvbox-themed Hyprland rice for Arch Linux.

## Preview
<img width="1920" height="1080" alt="Screenshot-2026-01-03_15:09:24" src="https://github.com/user-attachments/assets/7f5ed3f5-531d-4541-83ef-f41d0b3b1249" />

## Features
- **WM**: Hyprland
- **Bar**: Waybar with custom modules
- **Launcher**: Rofi
- **Terminal**: Kitty
- **Notifications**: Mako
- **Theme**: Gruvbox Material (custom #83a598 accent)

## Installation
```bash
# Clone the repo
git clone https://github.com/simpleog/arch-gruvbox
cd arch-gruvbox

# Install dependencies
sudo pacman -S hyprland waybar rofi rofi-emoji hypridle hyprlock hyprpicker \
       mako kitty wlogout brightnessctl nvim yazi thunar
paru -S hyprshade getnf

# Install Nerd fonts
getnf

# Backup your configs
cp -r ~/.config/hypr ~/.config/hypr.backup

# Copy configs
cp -r hypr ~/.config/
cp -r waybar ~/.config/
cp -r rofi ~/.config/
cp -r mako ~/.config/
cp -r kitty ~/.config/
cp -r wlogout ~/.config/
cp -r nvim ~/.config/

#Copy Wallpaper (optional)
cp Cat_at_Play.png ~/Pictures/Wallpapers/

# GTK Theme
cp -r Gruvbox-Material-Dark ~/.themes/
```

## Keybinds
See `hypr/keybinds.conf` for full list

## Credits
- Gruvbox theme by morhetz
- Astro Nvim https://astronvim.com/
