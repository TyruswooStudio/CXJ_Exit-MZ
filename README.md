# CXJ Exit v1.0.1 for RPG Maker MZ
By G.A.M. Kertopermono, a.k.a. GaryCXJk

The original MV edition of this plugin can be found on its creator's website, 
[GeryCXJk.com](https://area91.garycxjk.com/rmmv/plugins/misc/exit).

Since this plugin's author has generously placed it in the public domain,
the developers at [Tyruswoo Studio](https://www.tyruswoo.com/) have ported it
to RPG Maker MZ and are likewise placing this MZ edition in the public domain.

Mr. Kertopermono's original notes on this plugin are below,
and below them is the version history.

## About

As you all know HTML5 games don't generally need exit buttons. Neither do
mobile versions, as you can just Back or Home your way out. But with desktop
that's a whole different thing. You do want to get out without having to
resort to using CTRL+F4 or something similar.

This plugin adds this option to both the title screen as well as the Game
End option.

## Usage

After you add the plugin, you can set the parameters. They're pretty much
self-explanatory. "Text - Exit" and "Text - To Desktop" are the text labels
for each respective button. The first appears in the title screen, the
latter in the Game End window.

"Add to title" and "Add to Game End" both are boolean values, and determine
whether or not the new buttons should be added.

On non-desktop browsers the game won't add the exit options. They could be
made visible, but they don't work, so it's pretty useless to keep them.

## Plugin Commands

This plugin contains Plugin Commands. These are as followed:

### Exit
Exits the game. This can be executed for both desktop and browser-based
clients, but it would only work on desktop.

## Compatibility

This plugin overwrites the functions listed below, but still uses the old
version, either as the basis for the function or as a fallback. It is
advised to place this script below other scripts that use these functions.

- Scene_Title.prototype.createCommandWindow
- Window_TitleCommand.prototype.makeCommandList
- Scene_GameEnd.prototype.createCommandWindow
- Window_GameEnd.prototype.makeCommandList
- Game_Interpreter.prototype.pluginCommand

## Version History

**1.0.0** (2015-10-26)
* Initial release for RPG Maker MV

**1.0.1** (2015-10-27)
* Added script rename fallback

**1.0.1, MZ edition** (2022-11-01)
* Ported to RPG Maker MZ by McKathlin

## License

CC0 1.0 Universal (CC0 1.0)
Public Domain Dedication

The person who associated a work with this deed has dedicated the work to
the public domain by waiving all of his or her rights to the work worldwide
under copyright law, including all related and neighboring rights, to the
extent allowed by law.

You can copy, modify, distribute and perform the work, even for commercial
purposes, all without asking permission.

https://creativecommons.org/publicdomain/zero/1.0/