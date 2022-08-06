# Sway WM Config

My Configuration for the Sway Window Manager and related Programms.

---

## Required Programms

_All Programms are available directly through the Arch Repositories or through the AUR._

__sway__ Of course the window manager itself

__swayidle__ Programm that activates the lockscreen and disables the screen after a certain amount of time

__swaylock__ lockscreen

__alacritty__ fast and simple terminal

__fuzzel__ application launcher

__brightnessctl__ display brightness control

__pavumanager__ PulseAudio Volume Manager

__sov__ Workspace Overview

__waybar__ Status Bar

__ttf-font-awesome__ Font

__ttf-jetbrains-mono__ Font

__ttf-roboto__ Font

__noto-fonts__ Font

__noto-fonts-extra__ Font

---

## References and Tips

__Alacritty__ In [Alacritty](https://github.com/alacritty/alacritty) I use the [Night-Owl-Theme](https://github.com/sdras/night-owl-vscode-theme). The theme is originally for Visual Studio and the version for alacritty is found [here](https://github.com/alacritty/alacritty/wiki/Color-schemes).

__waybar__ I use a few lines of code from a  project called [riverwm](https://github.com/theCode-Breaker/riverwm/tree/main/waybar/river).

__brightnessctl__ This tool works fine on my system but a single backlight manager never works for every hardware configuration. You can find other tools on this [Arch Wiki Page](https://wiki.archlinux.org/title/Backlight).

---

## Installation

1. Install the required packages

    ```bash
    git clone 
    ```

2. Git clone the repository and copy the content in the .config folder in your home directory.

    ```bash
    cp sway-wm-config/* ~/.config/
    ```
