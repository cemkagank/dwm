# My build of dwm

> Includes all the patches that luke has.

## Used packages

- `alsa-utils` for audio control
- `blight` for brightness control
- `playerctl` for Media control
- `firefox` $BROWSER call changed with firefox
- `ranger` as the file manager
- mononoki nerd font is the default font i use

## Visual Changes
- Changed bar color to orange #ff4500
- decreased border px
- renamed tags with keywords

## Removed Stuff
> I have deleted the keys for the programs that I don't use
- neomutt
- pulseaudio
- sysact

## Changed Keybindings

> Keybindings have slightly changed
- mod+r for ranger
- XF86 Audio for controlling media volume or navigating media
- XF86 Brighhtness for controlling brightness

## Installation for newbs

```
git clone https://github.com/cemkagank/dwm
cd dwm
sudo make install
```


## Please install `libxft-bgra`!

This build of dwm does not block color emoji in the status/info bar, so you must install [libxft-bgra](https://aur.archlinux.org/packages/libxft-bgra/) from the AUR, which fixes a libxft color emoji rendering problem, otherwise dwm will crash upon trying to render one. Hopefully this fix will be in all libxft soon enough.
