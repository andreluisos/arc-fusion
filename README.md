### Manual Installation

Arch dependencies
* `sudo pacman -S autoconf automake sassc pkg-config optipng inkscape gnome-themes-extra gtk-engine-murrine`

Installation
* `./autogen.sh --prefix=/usr --disable-cinnamon --disable-gtk2 --disable-metacity --disable-unity --disable-xfwm --disable-plank --disable-openbox`
* `sudo make install`

## Uninstall

* `sudo make uninstall`
* `sudo rm -rf /usr/share/themes/{Arc,Arc-Darker,Arc-Dark}`

## Extras

### Arc KDE
A port of Arc for the Plasma 5 desktop with a few additions and extras. Available [here](https://github.com/PapirusDevelopmentTeam/arc-kde).

### Arc Firefox theme
A theme for Firefox is available at https://github.com/horst3180/arc-firefox-theme

### Arc icon theme
The Arc icon theme is available at https://github.com/horst3180/arc-icon-theme

### Chrome/Chromium theme
To install the Chrome/Chromium theme go to the `extra/Chrome` folder and drag and drop the arc-theme.crx or arc-dark-theme.crx file into the Chrome/Chromium window. The source of the Chrome themes is located in the source "Chrome/arc-theme" folder.

### Plank theme
To install the Plank theme, copy the `extra/Arc-Plank` folder to `~/.local/share/plank/themes` or to `/usr/share/plank/themes` for system-wide use.
Now open the Plank preferences window by executing `plank --preferences` from a terminal and select `Arc-Plank` as the theme.

### Arc-Dark for Ubuntu Software Center
The Arc Dark theme for the Ubuntu Software Center by [mervick](https://github.com/mervick) can be installed from [here](https://github.com/mervick/arc-dark-software-center). It solves readability issues with Arc Dark and the Ubuntu Software Center.
