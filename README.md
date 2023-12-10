***WORK IN PROGRESS*** 

# Kde Plasma rice

This is step by step guide to my kde plasma rice / customization. This guide is modular and does not require every step to be exactly same, feel free to experiment and mish mash your preferred options, this is possible thanks to KDE's modular and flexible structure.

## My Setup

- Kernel: 6.6.4
- Distribution: Arch Linux
- Resolution: 1920x1080
- Desktop Environment: KDE Plasma (X11)
- Window Manager: KWin
- GPU: Nvidia GeForce GTX 1660 Ti Mobile

## Wallpaper

As for wallpapers I found very talanted artist Abyss and used their anime styled landscape wallpaper, [here is link to their page](https://alphacoders.com/users/profile/283455/Abyss). You can find my selection of Abyss's wallpapers in `/wallpapers` directory.

To set wallpapers, right click on desktop and select "Configure Desktop and Wallpaper". Select "folder view" for "layout", "wallpaper type" as "slideshow", "positioning" as "scaled and cropped". Set "order" and "change every" options as you like, my preference is random every 1 hour. And then select the folder containing all your wallpapers.

## Panels

In my workflow I use two panels, one on top which contains application starter and application menu bar on left, watch and date in the middle, and virtual desktop preview and status bar on right, the second panel is in the bottom and can be called dock which contains pinned apps and active apps.

For panel at the top right click on desktop and select "add panel" and then "application menu bar". After that right click on dektop or panel itself and enter edit mode, in this mode you can add all necessary widgets inside your bar, to achieve same panel as mine, add application menu to the left side, right to it should be application menu which should already be in panel. Then add panel spacer rigth to them, then add time widget, then another panel spacer, then add virtual dektop preview widget and sistem tray widget to the further right. Also make panel floating from "more options" menu. Lastly you can set height of your panel, mine is 30 pixels.

![](/assets/top-panel.png "top panel")

For dock or panel at the bottom add new empty panel and them move it to the bottom in edit mode, make it floating and set allignment to the center, you two arrows at the right or left of your panel to set minimum and maximum size of your panel, my panel can maximize as far as screen goes and can minimize to a zero width but it never does because it always will contain pinned apps. Add icons only task manager widget and set height of your panel, mine is 60 pixels. Lastly select "auto hide" from "more options" selection to make panel automatically hide when not interacted, and pop up when mouse hits bottom of the screen.

![](/assets/dock.png "dock")

Don't worry if your panels are not rounded and not transparent, we will set this parameters in another sections.



