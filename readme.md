## Installation
- **Install i3** <br />
`sudo apt-get install i3` <br />
It will give You i3-wm, dunst, i3lock, i3status, and suckless-tools.
If i3-wm, dunst, i3lock, i3status, and suckless-tools are not installed automatically, just install them manually. <br />
`sudo apt-get install i3-wm dunst i3lock i3status suckless-tools` <br />

- **Then install some additional packages to make your desktop enjoyable** <br />
`sudo apt-get install compton hsetroot rxvt-unicode xsel rofi fonts-noto fonts-mplus xsettingsd lxappearance scrot viewnior`

## Explanations of Additional Packages
- Compton is a compositor to provide some desktop effects like shadow, transparency, fade, and transiton. 
- Hsetroot is a wallpaper handler. i3 has no wallpaper handler by default.
- URxvt is a lightweight terminal emulator, part of *i3-sensible-terminal*.
- Xsel is a program to access X clipboard. We need it to make copy-paste in URxvt available. Hit Alt+C to copy, and Alt+V to paste. 
- Rofi is a program launcher, similar with dmenu but with more options.
- Noto Sans and M+ are my favourite fonts used in my configuration.
- Xsettingsd is a simple settings daemon to load fontconfig and some other options. Without this, fonts would look rasterized in some applications.
- LXAppearance is used for changing GTK theme icons, fonts, and some other preferences.

## Copying Configurations
`git clone https://github.com/naresh335/i3-config.git` <br />

Or if You don't have git package installed, and have no willing to install it. 
Just use download as zip button on the top-right of this page, then extract it.
After that, Open *i3-starterpack* folder. Then copy the configurations to your home.
I mean if it's on *i3-starterpack/.config/i3/config*, copy it to *~/.config/i3/*.
If the folder doesn't exist on your home, just make it.
Do the same with all of the files inside *i3-starterpack* folder.
My dotfiles contains font, so refresh your fontconfig cache `fc-cache -fv` after You copy the font. <br />

**All in one command :** You can deploy this repository recursively using 
`git clone https://github.com/naresh335/i3-config.git && cp -a i2-starterpack/. ~`


## Link to base repository

https://github.com/addy-dclxvi/i3-starterpack.git` <br />
