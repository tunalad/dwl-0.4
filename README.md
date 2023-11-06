# tunalad's EPIC dwl fork

dwm for wayland. Trying to achieve the same as with my dwm fork

## Requirements

-   set `$TERMINAL` environment variable
-   wlroots
-   xorg-xwayland
-   wayland-protocols (make)

## Installaion

```
git clone https://github.com/tunalad/dwl.git
cd dwl
sudo make clean install
```

## Applied Patches

-   [alwayscenter](https://github.com/djpohly/dwl/wiki/alwayscenter)
-   [attachbottom](https://github.com/djpohly/dwl/wiki/attachbottom)
- [en-keycodes](https://github.com/djpohly/dwl/wiki/en-keycodes)
-   [moveresizekb](https://github.com/djpohly/dwl/wiki/moveresizekb) (moveresize, also I've slightly altered the patch)
-   [movestack](https://github.com/djpohly/dwl/wiki/movestack)
-   [pertag](https://github.com/djpohly/dwl/wiki/pertag)
-   [shiftview](https://github.com/djpohly/dwl/wiki/shiftview)
-   [terminal_envvar](https://gist.github.com/tunalad/2bba81acee2dbebdaa0275fcd4f82493) (environmentvars port)
-   [uselessgaps](https://github.com/djpohly/dwl/wiki/uselessgaps) (fullgaps alternative)

## Missing Patches

-   [actualfullscreen](https://dwm.suckless.org/patches/actualfullscreen/)
-   [alwaysontop](https://dwm.suckless.org/patches/alwaysontop/)
-   [autostart](https://dwm.suckless.org/patches/autostart/)
    - there is an autostart patch for dwl ([here](https://github.com/djpohly/dwl/wiki/autostart)), but it's like the [cool_autostart](https://dwm.suckless.org/patches/cool_autostart/)
    - update 2: there's no need for this either, you can just -s option `dwl -s $XDG_DATA_HOME/dwm/autostart.sh`
-   [fixborders](https://dwm.suckless.org/patches/alpha/)
    -   not required, dwl by itself does the transparency
-   [focusonnetactive](https://dwm.suckless.org/patches/focusonnetactive/)
-   [systray](https://dwm.suckless.org/patches/systray/)
    -   dwl doesn't come with a bar
-   [stackmfact](https://dwm.suckless.org/patches/stackmfact/)
    - I don't really use this option so it's not really even necessary?
