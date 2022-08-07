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
| __swaylock__ 			| lockscreen				| [GitHub](https://github.com/swaywm/swaylock) | [community](https://archlinux.org/packages/community/x86_64/swaylock/) |
| __wlogout__ 			| Logout screen with options		| [GitHub](https://github.com/ArtsyMacaw/wlogout) | [AUR](https://aur.archlinux.org/packages/wlogout) |
| __waybar__ 			| Status Bar				| [GitHub](https://github.com/Alexays/Waybar/) | [community](https://archlinux.org/packages/community/x86_64/waybar/) |
| __alacritty__ 		| fast and simple terminal		| [GitHub](https://github.com/alacritty/alacritty) | [community](https://archlinux.org/packages/community/x86_64/alacritty/) |
| __fuzzel__ 			| application launcher			| [CodeBerg](https://codeberg.org/dnkl/fuzzel) | [community](https://archlinux.org/packages/community/x86_64/fuzzel/) |
| __brightnessctl__ 		| display brightness control		| [GitHub](https://github.com/Hummer12007/brightnessctl) | [community](https://archlinux.org/packages/community/x86_64/brightnessctl/) |
| __pavucontrol__ 		| PulseAudio Volume Manager		| [freedesktop](https://freedesktop.org/software/pulseaudio/pavucontrol/) | [community](https://archlinux.org/packages/extra/x86_64/pavucontrol/) |
| __sov__ 			| Workspace Overview			| [GitHub](https://github.com/milgra/sov) | [AUR](https://aur.archlinux.org/packages/sov) |
| __ttf-font-awesome__ 		| Font					| [Font Awesome](https://fontawesome.com/) | [community](https://archlinux.org/packages/community/any/ttf-font-awesome/) |
| __ttf-jetbrains-mono__ 	| Font					| [jetbrains](https://jetbrains.com/lp/mono) | [community](https://archlinux.org/packages/community/any/ttf-jetbrains-mono/) |
| __ttf-roboto__ 		| Font					| [Google](https://material.google.com/style/typography.html) | [community](https://archlinux.org/packages/community/any/ttf-roboto/) |
| __noto-fonts__ 		| Font					| [Google Fonts](https://fonts.google.com/noto) | [extra](https://archlinux.org/packages/extra/any/noto-fonts/) |
| __noto-fonts-extra__ 		| Font					| [Google Fonts](https://fonts.google.com/noto) | [extra](https://archlinux.org/packages/extra/any/noto-fonts-extra/) |

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

2. Clone the repository

    ```shell
    git clone https://github.com/LetzteFee/sway-wm-config.git
    ```

3. Distribute the files

    ```shell
    mv sway-wm-config/* ~/.config/
    ```

---

## TODO

* include the wallpaper
* include the gtk theme and icons
* clean and finish the code
* check if all fonts are needed
