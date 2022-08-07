# Sway WM Config

My Configuration for the Sway Window Manager and related Programms. This repository does not have the purpose to contain my own up-to-date configuration but rather to provide a ready, clean and working configuration.

---

## Required Programms

_All Programms are available directly through the Arch Repositories or through the AUR._

| Programm			| Description				| Repository	| Linux Arch Package	|
|-------------------------------|---------------------------------------|---------------|-----------------------|
| __sway__ 			| the window manager itself		| [GitHub](https://github.com/swaywm/sway)	| [community](https://archlinux.org/packages/community/x86_64/sway/) |
| __swaybg__ | Wallpaper tool | [GitHub](https://github.com/swaywm/swaybg) | [community](https://archlinux.org/packages/community/x86_64/swaybg/) |
| __swayidle__ 			| controls lockscreen and backlight	| [GitHub](https://github.com/swaywm/swayidle) | [community](https://archlinux.org/packages/community/x86_64/swayidle/) |
| __swaylock__ 			| lockscreen				|		|			|
| __wlogout__ 			| Logout screen with options		|		|			|
| __waybar__ 			| Status Bar				|		|			|
| __alacritty__ 		| fast and simple terminal		|		|			|
| __fuzzel__ 			| application launcher			|		|			|
| __brightnessctl__ 		| display brightness control		|		|			|
| __pavumanager__ 		| PulseAudio Volume Manager		|		|			|
| __sov__ 			| Workspace Overview			|		|			|
| __ttf-font-awesome__ 		| Font					|		|			|
| __ttf-jetbrains-mono__ 	| Font					|		|			|
| __ttf-roboto__ 		| Font					|		|			|
| __noto-fonts__ 		| Font					|		|			|
| __noto-fonts-extra__ 		| Font					|		|			|

---

## References and Tips

__Alacritty__ In [Alacritty](https://github.com/alacritty/alacritty) I use the [Night-Owl-Theme](https://github.com/sdras/night-owl-vscode-theme). The theme is originally for Visual Studio and the version for alacritty is found [here](https://github.com/alacritty/alacritty/wiki/Color-schemes).

__waybar__ I use a few lines of code from a  project called [riverwm](https://github.com/theCode-Breaker/riverwm/tree/main/waybar/river).

__brightnessctl__ This tool works fine on my system but a single backlight manager never works for every hardware configuration. You can find other tools on this [Arch Wiki Page](https://wiki.archlinux.org/title/Backlight).

---

## Installation

1. Install the required packages

    ```shell
    yay -S sway swayidle swaylock wlogout waybar alacritty fuzzel brightnessctl pavumanager sov ttf-font-awesome ttf-jetbrains-mono ttf-roboto noto-fonts noto-fonts-extra
    ```

2. Git clone the repository and copy the content in the .config folder in your home directory.

    ```shell
    git clone 
    cp sway-wm-config/* ~/.config/
    ```
