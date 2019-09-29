Read the original dwm documentation over at the [official suckless website](https://dwm.suckless.org/).

## Patches applied

- [Alpha](https://dwm.suckless.org/patches/alpha/) - Enables transparency. Does require a third-party compositor installed like compton or xcompmgr.
- [Attachaside](https://dwm.suckless.org/patches/attachaside/) - Make new clients get attached and focused in the stacking area instead of always becoming the new master.
- Custom bar (don't quite have the source) - Provides blank space to put your own bar using something like polybar or lemonbar.
- [EWMHTags](https://dwm.suckless.org/patches/ewmhtags/) - Provides EWMH (Extended Window Manager Hints) support which in turn enables third party status bars to display tags.
- [PerTag](https://dwm.suckless.org/patches/pertag/) - Keeps layout, mwfact, barpos and nmaster per tag.
- [RotateStack](https://dwm.suckless.org/patches/rotatestack/) - Stack rotation moves a client from the bottom to the top of the stack (or the other way round). This effectively rotates the clients by one position clockwise (or CCW, respectively).
- [StatusPadding](https://dwm.suckless.org/patches/statuspadding/) - Makes the amount of horizontal and vertical padding in the status bar into configurable options.
- [VanityGaps](https://dwm.suckless.org/patches/vanitygaps/) - Enables gaps. Because why not?

## Why shift to i3 after so much hassle?

Getting the perfect status bar was an issue because I quite frankly didn't like the look of the default status bar and setting up polybar was easier in i3 for me. But for someone who is looking for a bare-bones window manager which is dynamic (the d in dwm), dwm is a pretty good choice IMO if, you're okay with all the patching that comes with it. On a side note I would like to mention that as you apply more and more patches, some of them start breaking and you will have to apply further patches manually.
