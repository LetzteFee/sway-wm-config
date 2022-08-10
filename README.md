# Sway WM Config

My Configuration for the Sway Window Manager and related Programms. This repository does not have the purpose to contain my own up-to-date configuration but rather to provide a ready, clean and working configuration.

---

## Required Packages

_All Programms are available directly through the Arch Repositories or through the AUR. The themes all are from [GNOME-LOOK](https://www.gnome-look.org/browse/)._

| Package			| Description				| Repository	| Download		|
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
| __wayshot-bin__ | Screenshot tool | [GitHub](https://github.com/waycrate/wayshot) | [AUR](https://aur.archlinux.org/packages/wayshot-bin)
| __ttf-font-awesome__ 		| Font					| [Font Awesome](https://fontawesome.com/) | [community](https://archlinux.org/packages/community/any/ttf-font-awesome/) |
| __ttf-jetbrains-mono__ 	| Font					| [jetbrains](https://jetbrains.com/lp/mono) | [community](https://archlinux.org/packages/community/any/ttf-jetbrains-mono/) |
| __ttf-roboto__ 		| Font					| [Google](https://material.google.com/style/typography.html) | [community](https://archlinux.org/packages/community/any/ttf-roboto/) |
| __noto-fonts__ 		| Font					| [Google Fonts](https://fonts.google.com/noto) | [extra](https://archlinux.org/packages/extra/any/noto-fonts/) |
| __noto-fonts-extra__ 		| Font					| [Google Fonts](https://fonts.google.com/noto) | [extra](https://archlinux.org/packages/extra/any/noto-fonts-extra/) |
| __graphite__ | GTK-Theme | [GitHub](https://github.com/vinceliuice/Graphite-gtk-theme) | [gnome-look](https://www.gnome-look.org/p/1598493) |
| __kora__ | Icon Theme | [GitHub](https://github.com/bikass/kora) | [gnome-look](https://www.gnome-look.org/p/1256209) |

---

## Installation

1. Install the required packages

    ```shell
    yay -S
    ```

2. Clone the repository

    ```shell
    git clone https://github.com/LetzteFee/sway-wm-config.git
    ```

3. Distribute the files

    ```shell
    mv sway-wm-config/* ~/.config/
    ```

4. Install the themes

5. Put your wallpaper in ~/Pictures/backgrounds/ and name it 01.jpg

---

## Optional Applications

Name|Description|Links
---|---|---
__X-Apps__|You probably need new applications. KDE Apps don't look really great in Sway and are often bloated anyway. GNOME Apps often have limited functionality and require a headerbar. That makes them looking inefficient. That is the reason I switched to X-Apps. X-Apps are programms developed by the linux mint team to work on all desktop environments and to have the right amount of features. Additionally, I use the filemanager Nemo which is not an X-App but it still is my favourite filemanager and it is developed by the linux mint team, aswell.|[arch wiki](https://wiki.archlinux.org/title/Cinnamon#Cinnamon_applications)
__Polkit__|Programms need polkit when they want to ask for higher permissions. _polkit-gnome_ is my polkit-gui of choice.|[Download](usr/lib/polkit-gnome/polkit-gnome-authentication-agent-1)
__XWayland__|makes running xorg on wayland possible|[arch wiki](https://wiki.archlinux.org/title/Wayland#XWayland)

---

## References and Tips

__Alacritty__ In [Alacritty](https://github.com/alacritty/alacritty) I use the [Night-Owl-Theme](https://github.com/sdras/night-owl-vscode-theme). The theme is originally for Visual Studio and the version for alacritty is found [here](https://github.com/alacritty/alacritty/wiki/Color-schemes).

__waybar__ I use a few lines of code from a  project called [riverwm](https://github.com/theCode-Breaker/riverwm/tree/main/waybar/river).

__brightnessctl__ This tool works fine on my system but a single backlight manager never works for every hardware configuration. You can find other tools on this [Arch Wiki Page](https://wiki.archlinux.org/title/Backlight).
