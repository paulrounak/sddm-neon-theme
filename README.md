# sddm-neon-theme
A neon theme for sddm.

# Preview
![12-06-2024-12-38-41](https://github.com/duckyfied/sddm-neon-theme/assets/172433021/4a5266eb-0252-4a9f-a7d5-fef06b93222e)

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
