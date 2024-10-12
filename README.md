# Kde Plasma rice

This is step by step guide to my kde plasma rice / customization. This guide is modular and does not require every step to be exactly same, feel free to experiment and mish mash your preferred options, this is possible thanks to KDE's modular and flexible structure.

screenshots:

![](/assets/rice1.png "ss")

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

Same can be applied to lock screen wallpapers through `Settings/Workspace Behaviour/Screen Locking/Appearance:Configure`.

## Panels

In my workflow I use two panels, one on top which contains application starter and application menu bar on left, watch and date in the middle, and virtual desktop preview and status bar on right, the second panel is in the bottom and can be called dock which contains pinned apps and active apps.

For panel at the top right click on desktop and select "add panel" and then "application menu bar". After that right click on dektop or panel itself and enter edit mode, in this mode you can add all necessary widgets inside your bar, to achieve same panel as mine, add application menu to the left side, right to it should be application menu which should already be in panel. Then add panel spacer rigth to them, then add time widget, then another panel spacer, then add virtual dektop preview widget and sistem tray widget to the further right. Also make panel floating from "more options" menu. Lastly you can set height of your panel, mine is 30 pixels.

![](/assets/top-panel.png "top panel")

For dock or panel at the bottom add new empty panel and them move it to the bottom in edit mode, make it floating and set allignment to the center, you two arrows at the right or left of your panel to set minimum and maximum size of your panel, my panel can maximize as far as screen goes and can minimize to a zero width but it never does because it always will contain pinned apps. Add icons only task manager widget and set height of your panel, mine is 60 pixels. Lastly select "auto hide" from "more options" selection to make panel automatically hide when not interacted, and pop up when mouse hits bottom of the screen.

![](/assets/dock.png "dock")

Don't worry if your panels are not rounded and not transparent, we will set this parameters in another sections.

## Themes and adjustments

For this rice I used avaliable themes and adjusted them manually for my needs, but don't worry I will share customized theme files so you don't bother with manual work I have gone through. But ability to understand theme files and editing vectors will grant you freedom with your rice.

All the topics below are options for theming in `Settings/Appearance`

### Global theme

In my rice global theme does not have much effect (at least I hope so) because I use different theme for every aspect of desktop. It is set to Breeze Dark, but I am not sure which parts it affects.

### Application style

For application style I use vanilla Breeze.

### Plasma style

For plasma style I use my custamisation of `ROUNDED COLOR OPAQUE` theme. This theme gives us roundiness and opaqueness for our windows. In my customized file I mainly increased roundness and made window more opaque to achieve look I wanted.

Custom theme file is under `custom themes` directory named `ROUNDED-COLOR-OPAQUE-CUSTOM`, to use it copy file to `.local/share/plasma/desktoptheme` directory and select it from `Settings/Appearance/Plasma Style`.

### Window decorations

For window decorations I also used available theeme and customised it slightly. The theme I customised is `Sweet-Dark-transparent`, in my customisation I only changed colors for maximize and restore buttons from purple to green.

Customised file is in `custom themes` directory and named `Sweet-Dark-transparent-Custom`. Copy it to your `local/share/aurorae/themes` directory and activate in `Settings/Appearance/Window Decorations`.

### Fonts, Icons, Cursors

My fonts are default. Icons are set `Flatery-Black` (you can find it in store). And cursors are set to `Adwaita`.

## Colors

As you can see I have not mentioned `Colors` in `Theme` section. It is because I use different approach to set colors, and this approach achieves dinamic color schemes depending on your wallpaper. Getting your color scheme from wallpaper makes your desktop look feel complete.

luisbocanegra's github project named `kde-material-you-colors` helps us achieve this functionality. [here is link to project's github page](https://github.com/luisbocanegra/kde-material-you-colors.git). I will not mention how to install this widget as it is explained clearly in project's github page.





