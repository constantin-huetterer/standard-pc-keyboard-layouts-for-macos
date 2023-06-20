# Standard PC (Win/Linux) Keyboard Layouts for MacOS
If you are switiching between MacOS and Windows/Linux systems regularily, you might be bothered by the fact that special caracters like `@`, `(`, `)`, `{`, `}`, `[`, `]`, etc. are mapped differently in MacOS. 

If you are using an external keyboard and don't use touch typing this is worse, since you cannot rely on the symbols on the key-caps anymore.
If you touch type, you have to memorize both layouts and switch between them.

This Repository provides keyboard layouts for MacOS, that will map most keys to their Windows/Linux-PC-Counterparts, improving usability of external keyboards and reducing mental load when touch typing and switching between the different operating systems. 

> **Note** \
> __I am not the Author of the keyboard layouts.__ I found the first one I was looking for (the German layout) [here](https://www.hackintosh-forum.de/forum/thread/54069-mx-keys-für-mac-unter-windows-mappen/). After a little digging I found [this post](https://www.xadomir.de/betriebssysteme/mac-os/23-deutsches-tastatur-layout-fuer-deinen-mac.html) that explains the origin of the file: the `.dmg` of [Ukelele 2.2.8](https://software.sil.org/ukelele/).
> The purpose of this repository is for my own reference and to spread the files, because (at least for me) it was hard to find a working solution quickly. I am also including information on how to quickly setup and modify it. Please support Ukulele if you found the files useful.

# Setup
Since this was my original use case, I am providing the setup example for the German keyboard layout. Therefore I have used the German setting names with rough translations in brackets. Swap the `LogitechGerman.keylayout` file for the one you need.

1. Download/Clone the keyboard layout file for your language from this Repo
2. Copy/Paste or move the layout file into `Library/Keyboard Layouts` (see table below for other options)
   | | |
   |-|-|
   | /Library/Keyboard Layouts | available to all users on the machine |
   | ~/Library/Keyboard Layouts | available to the user only |
   | /Network/Library/Keyboard Layouts | available to all users on the network |
3. (Optional) Sign out of your user account and log back in or restart your Mac
4. To activate the keyboard layout, go to "Systemeinstellungen" (System Settings) > "Tastatur" (Keyboard) > "Eingabequellen" (Input Sources) > "Bearbeiten ..." (Change) \
   ![image](https://github.com/constantin-huetterer/german-windows-keyboard-layout-for-macos/assets/60255589/255b10df-ffe1-4e13-9b45-cb2eced8fc53)
5. Select the `+` Symbol in the bottom left corner and then search for "Andere" (Other) in the dropdown List. There you should find the Logitech German Layout that you then add via "Hinzufügen". \
   ![image](https://github.com/constantin-huetterer/german-windows-keyboard-layout-for-macos/assets/60255589/16535b89-a9d9-4449-abd8-8d60da879984) \
   (In the picture it is added already and therefore greyed out)
6. Once you have added the keyboard layout, you can select it in the top right corner (status bar). \
   ![image](https://github.com/constantin-huetterer/german-windows-keyboard-layout-for-macos/assets/60255589/c79c055b-6321-4130-bc2c-e3039e4221da)

# Customizing the file
You can use [Ukelele](https://software.sil.org/ukelele/) to open and edit the keyboard layout.

# Remapping the modifier keys
You can also remap the modifier keys under System Preferences → Keyboard → Modifier Keys. \
![image](https://github.com/constantin-huetterer/german-windows-keyboard-layout-for-macos/assets/60255589/32cf9bdb-7e9c-4859-bd04-8e41ff8f1ef5)

# Other solutions
- Remap the keys with [Karabiner](https://karabiner-elements.pqrs.org)
- Feel free to issue a PR if you are aware of other solutions
