FVWM It's a tiling window manager too
-------------------------------------
FVWM -- The F is for *F*inally got around to writing a tiling window manager configuration. I saw ratpoison pack in the day and liked the general idea -- but sometimes a tiling window manager just isn't great (like transient windows, which are just a little weird). I figured FVWM, being configurable, could work just fine as a tiling window manager, and when I don't feel like tiling -- it's still FVWM so it can do the window thing too.

This configuration makes heavy use of modifier 3, which I mapped to my windows by having an `.Xmodmap` with the following:
```clear Mod4
add Mod4 = Super_R Hyper_L
clear Mod3
add Mod3 = Super_L```
I had to clear Mod4 because it was also mapped to Super_L... That may not be the case in your distro.
