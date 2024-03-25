# Hyprland dotfiles

## Dependencies
`hyprland` : wayland compositor  
`swww` : wallpaper daemon  
`waypaper` : wallpaper selector  
`hyprlock` : lockscreen  
`dunst` : notifications  
`rofi` : app launcher and powermenu  
`kitty` : terminal emulator  
`starship` : zsh prompt  
`zsh` : shell  
`dolphin` : file manager  
`waybar-cava-git` : status bar  
`playerctl` : mpris controller  
`Iosevka Nerd Font` : nerd font, used everywhere  
`Commit Mono Nerd Font` : font for sidebery (firefox sidebar)  
`zoxide` : cd replacement  
`eza` : ls replacement

## Other cool things (optional)
`termdown` : terminal clock with `termdown -f larry3d -z -Z "%H:%M"`  
`spicetify` : spotify themes and extensions  
`text theme` : spicetify theme  
`tomato.c` : pomodoro timer with ambient noise (https://github.com/gabrielzschmitz/Tomato.C)  

## How to install

### 1. Install all the Dependencies
You can find most of them in official arch repos and AUR

### 2. Install Firefox CSS
It's EdgyArcFr: https://github.com/artsyfriedchicken/EdgyArc-fr/

### 3. Install start page
https://gitlab.com/fazzi/startpage  
I recommend starting a local server with the start page by putting `python -m http.server PORT -d /PATH/TO/STARTPAGE` in your hyprland.conf and then using the `new tab override` extension to set it as new tab

### 4. Install configs
Clone the repo  
Copy contents of `config` folder to $HOME/.config  
Rename `zshrc` to .zshrc and copy to $HOME  
Copy `p10k.zsh` to $HOME

### 5. Install Wallpaper
Move wallpaper to any directory and select it with waypaper  

### 6. Profit

## Screenshots

![screenshot 1](https://github.com/i-am-a-llama/hyprland-dotfiles/blob/f5b25797f14d50c56f938ad4627992fb6e845abb/assets/screenshots/screenshot_1.png)  
![screenshot 2](https://github.com/i-am-a-llama/hyprland-dotfiles/blob/f5b25797f14d50c56f938ad4627992fb6e845abb/assets/screenshots/screenshot_2.png)  
![screenshot 3](https://github.com/i-am-a-llama/hyprland-dotfiles/blob/f5b25797f14d50c56f938ad4627992fb6e845abb/assets/screenshots/screenshot_3.png)
