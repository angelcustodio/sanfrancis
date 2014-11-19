# San Francisco Font for OS X (Yosemite)

Replace Helvetica Neue on your Mac with San Francisco, the Apple Watch font.

The font has been adapted from San Francisco Display, the new typeface for the Apple Watch.
Inspired by jenskutilek's [Fira System Font Replacement](https://github.com/jenskutilek/FiraSystemFontReplacement) and supermarin's [YosemiteSanFranciscoFont](https://github.com/supermarin/YosemiteSanFranciscoFont)

![example](https://raw.githubusercontent.com/angelcustodio/sanfrancis/master/sweet.png)

## How to install:
1. [Download the zip](https://raw.githubusercontent.com/angelcustodio/sanfrancis/master/SystemSanFrancisco.zip)
2. Copy _all_ the font files into `~/Library/Fonts` on your Mac *(protip: press `cmd+shift+g` while in Finder to type the path directly)*
4. Run `sudo chown root:wheel /Library/Fonts/System\ San\ Francisco*` to set the proper ownership of the font files
5. Repair Disk Permissions `diskutil repairPermissions /`
3. Log out and log back in to apply the changes

## How to uninstall:
1. Go to `~/Library/Fonts` on your Mac and delete the files starting with `System San Francisco Display`
2. Log out and log back in to apply the changes

## How does it work?
These San Francisco fonts have a special name table with names identical to those of the system fonts. Because the font folder `~/Library/Fonts` takes precedence over the fonts which are in `/System/Library/Fonts`, these specially crafted fonts are used for the user interface instead of the real system fonts. The original system fonts are not deleted or modified in any way.

I assume no copyright over these fonts, nor any liability for improper installation or improper use. Use of these fonts should conform to Apple's express copyright and rules.
