# tunalad's EPIC dwl fork

dwm for wayland. Trying to achieve the same as with my dwm fork

## Requirements

-   set `$TERMINAL` environment variable
-   monospaced font (`ttf-dejavu`)
-   `libx11`
-   `libxft`
-   `libxinerama`

## Installaion

```
git clone https://github.com/tunalad/dwm.git
cd dwm
sudo make clean install
```

## Patches applied

-   [alwayscenter](https://github.com/djpohly/dwl/wiki/alwayscenter)
-   [attachbottom](https://github.com/djpohly/dwl/wiki/attachbottom)
-   ¤ [autostart](https://github.com/djpohly/dwl/wiki/autostart)
-   [moveresizekb](https://github.com/djpohly/dwl/wiki/moveresizekb) (moveresize)
-   [movestack](https://github.com/djpohly/dwl/wiki/movestack)
-   [pertag](https://github.com/djpohly/dwl/wiki/pertag)
-   ¤ [shiftview](https://github.com/djpohly/dwl/wiki/shiftview)
-   ¤ [vanitygaps](https://github.com/djpohly/dwl/wiki/vanitygaps) (fullgaps alternative)

## Missing Patches

-   [actualfullscreen](https://dwm.suckless.org/patches/actualfullscreen/)
-   [alwaysontop](https://dwm.suckless.org/patches/alwaysontop/)
-   [environmentvars](https://dwm.suckless.org/patches/environmentvars/)
-   [fixborders](https://dwm.suckless.org/patches/alpha/)
    -   not required, dwl by itself does the transparency
-   [focusonnetactive](https://dwm.suckless.org/patches/focusonnetactive/)
-   [systray](https://dwm.suckless.org/patches/systray/)
    -   dwl doesn't come with a bar
-   [stackmfact](https://dwm.suckless.org/patches/stackmfact/)
