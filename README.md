# dwm - Dynamic Window Manager

dwm is a fast and lightweight tiling window manager for X.

This is my build of dwm for FreeBSD. I have added all my changes in the config.def.h file so after build dwm you can keep playing and make changes to your own config.h and still easily go back to mine if needed.

![Desktop Image](https://raw.githubusercontent.com/TechMizu/dwm/master/desktop.png)
Note
---------
I've changed the config.mk file from the orignal to make it work with FreeBSD, but the original config.mk file can be found in the official repository.

# Patches applied
- Alternative Tags.
- Bar Padding.
- PerTag.
- TileGap.
- Center Master.
- No Border.
- ~Center Window Name~.
- Fancy Bar.
- Attach Aside.

# Installation
> make clean install

root permission (sudo or doas) may be require.

Call dwm from .xinitrc like so: 
> exec dwm  
or  
> exec $HOME/.config/dwm

Depending where you cloned and make dwm.

For any aditional keybindings please refer to config.h

# Things worth mention
I use:
- Alacritty
- dmenu
- qutebrowser
- neovim
- compton
- feh
- nnn
- zsh
- i3lock
- Nerd Fonts
- VSCode

The unicode characters I am using as alternative tags and many more can be find here: https://www.nerdfonts.com/cheat-sheet.  Install the Nerd Font pkg.
