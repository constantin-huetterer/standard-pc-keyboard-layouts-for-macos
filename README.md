# Standard (German) Keyboard Layout for MacOS
If you are switiching between MacOS and Windows/Linux systems regularily, you might be bothered by the fact that special caracters like `@`, `(`, `)`, `{`, `}`, `[`, `]`, etc. are mapped differently in MacOS. 

If you are using an external keeboard and don't use touch typing this is worse, since you cannot rely on the symbols on the key-caps anymore. 
If you touch type, you have to memorize both layouts and switch between them.

This Repository provides a (German) keyboard layout for MacOS, that will map most keys to their Windows/Linux-PC-Counterparts, improving usability of external keyboards and reducing mental load when touch typing and switching between the different operating systems. 
I might expand the repo to include keyboard layouts for other languages as well.

> **Note** \
> __I am not the Author of this keyboard layout file.__ The purpose of this repository is to spread the file, because (at least for me) it was very hard to find. I am also including information on how to Setup and modify it.

# Setup
I am assuming that you speak German if you want to install a German keyboard layout. Therefore I have used the German setting names with rough translations in 

1. Download/Clone the keyboard layout file from this Repo
2. Copy/Paste or move the layout file into `Library/Keyboard Layouts`
3. (Optional) Sign out of your user account and log back in or restart your Mac
4. To activate the keyboard layout, go to "Systemeinstellungen" (System Settings) > "Tastatur" (Keyboard) > "Eingabequellen" (Input Sources) > "Bearbeiten ..." (Change)
   ![image](https://github.com/constantin-huetterer/german-windows-keyboard-layout-for-macos/assets/60255589/255b10df-ffe1-4e13-9b45-cb2eced8fc53)
5. Select the `+` Symbol in the bottom left corner and then search for "Andere" (Other) in the dropdown List. There you should find the Logitech German Layout that you then add via "Hinzufügen".
   ![image](https://github.com/constantin-huetterer/german-windows-keyboard-layout-for-macos/assets/60255589/16535b89-a9d9-4449-abd8-8d60da879984) \
   (In the picture it is added already and therefore greyed out)
6. Once you have added the keyboard layout, you can select it in the top right corner (status bar). \
   ![image](https://github.com/constantin-huetterer/german-windows-keyboard-layout-for-macos/assets/60255589/c79c055b-6321-4130-bc2c-e3039e4221da)

# Customizing the file
You can use [Ukelele](https://software.sil.org/ukelele/) to open and edit the keyboard layout.

# Remapping the modifier keys
You can also remap the modifier keys under System Preferences → Keyboard → Modifier Keys.
![image](https://github.com/constantin-huetterer/german-windows-keyboard-layout-for-macos/assets/60255589/32cf9bdb-7e9c-4859-bd04-8e41ff8f1ef5)

# Other solutions
- Remap the keys with [Karabiner](https://karabiner-elements.pqrs.org)
- Feel free to issue a PR if you are aware of other solutions
