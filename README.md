# Wine Prefix Scripts

There are other tools, most notably PlayOnLinux, that can automate the creation and population of independent prefixes for your favorite Wine programs and/or games.  But they come with enough additional automation that WineHQ will reject tests involving them.

These scripts are quite minor, by comparison; you can use the scripts to make a blank wine session on a new prefix, and then launch a new xterm or screen session that simply uses the prefix.

## Commands

* *mkwineprefix:* Create a wine prefix using all default settings.
* *mkwine32prefix:* If run from a 64-bit system, this will force the prefix to be 32-bit.
* *wine-shell:* Uses the screen program to launch a shell with $WINEPREFIX set.
* *wine-term:* Uses the xterm program to launch an xterm with $WINEPREFIX set.

All new prefixes are made in ~/.wineprefix.
