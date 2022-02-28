# SoulArchDots
Full dotfiles for my SoulArch rice

# General Info
OS: EndeavourOS

Terminal: Alacritty

Bar: Polybar

WM: [Rounded i3-gaps](https://github.com/resloved/i3 "Rounded i3-gaps")

Fetch: neofetch

Music Player: ncmpcpp

(!!!PLEASE SUPPORT THIS BAND!!!) [Soulmass](https://soulmass.bandcamp.com/)

Editor: [NVChad](https://github.com/NvChad/NvChad)

NVChad Theme: tokyodark

File Manger: Nautilus

Shell: fish

Fish Theme: Dracula

Powermenu/launcher: Rofi

Wallpaper: 

![thumb-1920-860193](https://user-images.githubusercontent.com/17256359/155949651-c2cbeb18-89a4-43e7-997e-184351a32524.png)

Neofetch Image: 

![ds-1](https://user-images.githubusercontent.com/17256359/155950035-834f7ec7-952a-4a6c-8dbb-80b0b4158ef4.jpg)


# Dependencies (all in pacman)

mpd

w3m

pulseaudio

pavcuontrol

(if on laptop) optimus-manager

(for bluetooth) blueman, bluez-utils (AUR)

(for screenshots) xclip, scrot

# Notes

IMPORTANT: I set the polybar up to use only the forest theme, which is where the config files are located. I have only included the forest folder as well as necessary scripts in my .config/polybar directory, so if you plan on using any other theme, you may need to copy and paste the configs into another folder. I have done a similar thing with rofi, using the launchers/ribbon configs. These are also set in the i3 config for my launcher binding and polybar on startup.

For neofetch image, I could not for the life of my figure out how to set it up in the default config. I made a simple script to run the command that says to use w3m and an image, and placed it in my /bin folder. This way i can just run the command "nf" from anywhere in my terminal. This script is included. The image is located in the ~/.config/i3 directory.

[Bluetooth module](https://github.com/msaitz/polybar-bluetooth) and [Optimus-Manager](https://github.com/OscarSanner/polybar-optimus-manager) module scripts were slightly modified, but everything needed should be included. I have set everything to be in the .config directory with nothing user specific, so everything should be ready out of the box. The only thing a tad bit strange is my i3 config, since I use different keybindings and there are some unnecessary comments left over from default config/copy and pasted bindings for volume control. 

Fish greeting was changed via command:

```set fish_greeting "This terminal awakened from the horror in a realm apart from your's..."```

# Installation

Everything is ready to go right out of the box. I have changed i3 keybinds to my personal liking, so those may require tweaking, but everything else is pretty standard. First backup any config files that you already have just to be safe, then copy everything in the repo to your /home/user directory. Restart i3, chmod the .sh files in polybar, rofi, as well as the nf file (if necessary) and everything should be set!


# Screenshots

![screenshot_20220228_030605](https://user-images.githubusercontent.com/17256359/155956212-fe55c88a-8b47-4b64-9d55-c4c9127c6939.png)




