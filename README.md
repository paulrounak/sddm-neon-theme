# sddm-neon-theme
A neon theme for sddm.

# Preview
![preview](https://github.com/duckyfied/sddm-neon-theme/assets/172433021/87480588-9b9c-4a84-a394-776f15459289)


# Install Dependencies
```sh
yay -S qt5-graphicaleffects qt5-quickcontrols2 qt5-svg sddm
```

# Install
1. Clone this repository, copy fonts to `/usr/share/fonts/`:

   ```sh
   sudo git clone https://github.com/duckyfied/sddm-neon-theme.git /usr/share/sddm/themes/sddm-neon-theme
   sudo cp /usr/share/sddm/themes/sddm-neon-theme/Fonts/* /usr/share/fonts/
   ```

2. Then add
    ```sh
   [Theme]
   Current=ssdm-neon-theme
   ```
   to `/etc/sddm.conf`. Here is a command to do so:
   ```sh
    sudo echo "[Theme]
    Current=sddm-neon-theme" | sudo tee /etc/sddm.conf
   ```
