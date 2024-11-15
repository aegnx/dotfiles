# aegnx's dotfiles

hello, here are my dotfiles (still in progress, i can make folders now thanks to glocean aka colgate)

its basically my own implementation of catppuccin macchiato (the colors may be inconsistent, but i like them this way)

I took inspiration from kaizen's [dotfiles](https://github.com/kzndotsh/dotfiles)

this is JUST i3, st/alacritty, polybar, and a picom fork config

the gtk theme is located down there!

ok lets go

# PREREQUISITES

pijulius' old picom fork branch, at [pijulius/picom/tree/implement-window-animations](https://github.com/pijulius/picom/tree/implement-window-animations)

download it as a zip file and then unzip it into a folder, then use ninja and meson according to the instructions (instructions in the github link above)

i3wm, polybar, nitrogen/feh (i use nitrogen), "JetBrainsMono Nerd Font" (or any nerd font, you just gotta change config strings)

you can use [getnf/getnf](https://github.com/getnf/getnf) to get your nerd fonts!

GTK themes

[GTK4 (i used Catppuccin-Dark-Macchiato-BL-MB.zip)](https://www.pling.com/p/1715554/) and [GTK3 (you can install them yourself if ur not on gentoo ig)](https://wiki.gentoo.org/wiki/Catppuccin)

# INSTALLATION
just git clone them into your home dir and copy the files you want/need:

``git clone https://github.com/aegnx/dotfiles && cd dotfiles``

for example:

``mkdir ~/.config/picom/ && cp ~/dotfiles/config/picom/picom.conf ~/.config/picom/picom.conf``

# CLOSING THOUGHTS

hope you liked this, if you wanna tell me that 1 bar is better than two, I ALREADY KNOW.

machine girl music gave me the power to go thru this

enjoy your hyprland-esque X11 wm!
