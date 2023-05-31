# rofi-wifi-menu
A Wi-Fi menu written in bash with custom icons and indication of currently connected network. Uses rofi and nmcli. Forked from [ericmurphyxyz](https://github.com/ericmurphyxyz/rofi-wifi-menu).

![Screenshot of rofi-wifi-menu](https://github.com/hrvadl/rofi-wifi-menu/assets/93580374/b310a8b5-7a2f-43b7-90e6-5158278bcf06)

### Installation

Install `nmcli` and `rofi` with your package manager. If you want to use the icons, set your Rofi font to a [JetBrains Mono font](https://github.com/JetBrains/JetBrainsMono). Then run the following commands:
 
```
git clone https://github.com/ericmurphyxyz/rofi-wifi-menu.git
cd rofi-wifi-menu
bash "./rofi-wifi-menu.sh"
```

You'll probably want to put the script in your `$PATH` so you can run it as a command and map a keybinding to it.
