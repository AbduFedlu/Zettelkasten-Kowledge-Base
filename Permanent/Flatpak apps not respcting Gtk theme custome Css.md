---
title: Flatpak apps not respcting Gtk theme custome Css
date: 2026-07-10
tags:
  - "#linux"
  - "#troubleshoot"
  - "#archlinux"
slip box: "[[Linux]]"
---


## Note 


# Flatpak GTK Override Instructions



- Make sure to install and Enable the adw-gtk3 theme

   ```flatpak install flathub org.gtk.Gtk3theme.adw-gtk3
        flatpak override --user --env=GTK_THEME=GTK
   ```



- Then running this to Allow the gtk css files to be accessed by Flatpak apps.
```bash
flatpak override --user --filesystem=xdg-config/gtk-3.0
flatpak override --user --filesystem=xdg-config/gtk-4.0
```

## Connected Idea 





## Reference and Source

Google Search AI Response 

