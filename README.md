# btw-i-use-arch
A modification on Variety, the desktop wallpaper switcher, to watermark the Arch Linux logo and display your true superiority.

## Setup

Clone with 
```bash
git clone --recurse-submodules
```

Install variety, the desktop wallpaper switcher. Find the location of the "set_wallpaper" script (usually $HOME/.config/variety/scripts).

Modify the first line of the set_wallpaper.patch with the correct script location. Also replace the "GIT_REPO" keyword with the absolute location of where you cloned this repo. 

Finally, apply patch with
```bash
patch -d/ -p0 < set_wallpaper.patch
```

Happy Arching!
