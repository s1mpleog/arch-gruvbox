# Arch Gruvbox Rice

My personal Gruvbox-themed Hyprland rice for Arch Linux.

## Preview
<img width="1920" height="1080" alt="preview" src="https://github.com/user-attachments/assets/ab16a24b-ea3e-423f-a236-b3f865be7a7d" />

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
       mako kitty wlogout brightnessctl
paru -S hyprshade

# Backup your configs
cp -r ~/.config/hypr ~/.config/hypr.backup

# Copy configs
cp -r hypr ~/.config/
cp -r waybar ~/.config/
cp -r rofi ~/.config/
cp -r mako ~/.config/
cp -r kitty ~/.config/
cp -r wlogout ~/.config/

# GTK Theme
cp -r Gruvbox-Material-Dark ~/.themes/
```

## Keybinds
See `hypr/keybinds.conf` for full list

## Credits
- Gruvbox theme by morhetz
