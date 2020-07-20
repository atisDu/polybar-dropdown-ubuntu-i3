## Preview

## Dark
![Dark](/preview/dark.png)
<br />
## Light
![Light](/preview/light.png)


- **## FIRST OF ALL
- **move tablet_mode file to /usr/local/bin



## Details
- **Distro** Ubuntu
- **WM** i3
- **Music Player** ncmpcpp, mpd, mpc
- **Launcher** Rofi
- **Panel** polybar drop down menus
- **urxvt
- **etc,etc.

## Other prerequisites

- **xdotool**
- **ttf-dejavu (or change the font to whatever you want)**
- **ttf-font-awesome**
- **Iosevka Nerd Font**

- **Some scripts expect i3/scripts/ to be in PATH**


## Relevant files

- **.config/i3/tablet_mode

- **.config/i3/scripts/polybar_modules/tablet_launcher & tablet_options

- **.config/polybar/config-tablet

- **.config/polybar/scripts/styles.sh


## Relevant lines 

- **exec_always --no-startup-id ~/.config/i3/scripts/tablet_mode

- **bindsym $mod+BackSpace exec --no-startup-id ~/.config/i3/scripts/polybar_modules/tablet_options toggle
