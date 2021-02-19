# GNOME Shell Recent(item)s

Recent(item)s adds an indicator to gnome shell panel to quickly navigate recent open files.

This is a fork from Leonardo Bartoli's Recent(items)s repo, to add more more privacy
https://github.com/leonardo-bartoli/gnome-shell-extension-Recents

Tested on 3.38.2

### Features:

- purge all recent items
- folders/files items excluded from search (regex pattern support)
- auto-purge from Recents, items excluded upon any search made
- ability to remove individual items
- search box ignoring excluded items
- support shortcut to open indicator menu
- open containing folder on right click

### Exclusion Pattern example

```
~/(?:Images|Documents|Vid[eé]os)/[pP]rivate/
```


### Installation


Installation from git

```
git clone git://github.com/mathdesc/gnome-shell-extension-Recents.git
cd gnome-shell-extension-Recents
mkdir ~/.local/share/gnome-shell/extensions/Recents@mathdesc.yahoo.Fr
cp -r ./ ~/.local/share/gnome-shell/extensions/Recents@mathdesc.yahoo.Fr
```

Restart the shell and then enable the extension.

---

### Screenshot

![Screenshot](https://raw.githubusercontent.com/mathdesc/gnome-shell-extension-Recents/master/data/screenshot.png)

![Screenshot-autopurge](https://raw.githubusercontent.com/mathdesc/gnome-shell-extension-Recents/master/data/screenshot-purge.png)

