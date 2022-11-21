# UHK-Viewer v5


## Purpose
Add some nice features I missed on the original [UHK agent](https://github.com/UltimateHackingKeyboard/agent).
It doesn't replace the original agent in any way, and is not my intention. In fact, UHK Viewer hasn't many features, but those included are imo enough powerful to justify the efforts of exporting the UHK configuration, handle the file in UHK-Viewer and import again to the keyboard.

The origin of this project was to support the macros released by [Karel on his forked firmware](https://github.com/kareltucek/firmware), but after the release of the version 9 (version 5 for the configuration files) and the inclusion of smart macros it lost a bit of the usefulness.
Also, the configuration files with the inclusion of up to 12 layers, made the old version incompatible.
If you want to keep an old karel's firmware version you should use [my old UHK Viewer](https://github.com/IzK666/UHK-Viewer)

Nevertheless, the main reason to create a fork of my original project is to keep supporting the missing features of agent, like converting the old macro syntax to the new one and the ability to copy/paste single layers.

**If you want to give it a try, you can use the [online version](https://izk666.github.io/UHK-Viewer-v5)**

## Features
- General
	- Update old configuration files to the new version. *It'll be done automatically once the file is loaded.*
	- Old Karel macros will be modified to be compatible with the new format
	- Smart macros will be enabled automatically. *A new special macro will be created*

- Merge configurations. You can import keymaps and macros from other configuration files.

- Keymaps
	- View keymaps *(not the modules)*
	- Copy/paste/clear half side layers. *The modules of each side will be copied/pasted as well, but not cleared!*
	- Rename keymap name and abbreviations. *It will update any keymap switch from keys, as well from macros.*
	- Delete keymaps. *It will remove any keymap switch from keys and comment macro calls.*
	- Duplicate keymaps
	- Create blank keymaps
	- Add/Remove layers

- Macros
	- View macros
	- Rename macros. *It will modify any keymap switch from keys, as well from macros.*
	- Delete macros. *It will remove any keymap switch from keys and comment macro calls.*
	