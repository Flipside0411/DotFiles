# Pop OS: Things to do after installation

---

1. **Update the OS:** Launch Pop! Shop, click the installed tab, install all
   available Operations System Update
1. **Install ZSH**

```
sudo apt-get install zsh
```

**Oh-my-zsh** <https://ohmyz.sh/>

```
sh -c "$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```

[_Install Powerline10k_](https://github.com/romkatv/powerlevel10k)

```
git clone --depth=1 https://github.com/romkatv/powerlevel10k.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/themes/powerlevel10k
```

3. **Add Favorite apps to dash:** Add System

   - [ ]Brave Browser
   - [ ]NVim
   - [ ]Alacritty
   - [ ]Atom
   - [ ]Foxit
   - [ ]Okular
   - [ ]DropBox
   - [ ]

4. **Set ALT+TAB to switch windows** Open settings and find Keyboard shortcuts.
   Search for 'Switch windows' and map to ALT+TAB.

5. **Media Codecs:**

```
sudo apt-get install ubuntu-restricted-extras
```

5. **Enable TRIM for SSD drives (for extending life):**

```
sudo systemctl enable fstrim.timer
```

6. **Install 'preload' for faster appllication startup:**

```
sudo apt-get install preload   (requires restart)
```

7. **Firewall:** (search for gufw)

8. **Gnome Tweaks from Pop Shop**
   Customize Fonts:
   -Scaling Fonts:

9. **Neofetch:** for displaying system information:

```
sudo apt install neofetch
```

10. **LibreOffice**

    - [_Microsoft Icons_](https://www.deviantart.com/charliecnr/art/Office-2013-theme-for-LibreOffice-512127527)
    - [_English Dictionaries_](https://extensions.libreoffice.org/extensions/english-dictionaries)
    - [*Microsoft Fonts*]

    ```
    sudo apt install ttf-mscorefonts-installer
    ```

11) **PDF editor**
    _Foxit
    _ Okular

12) **Microsoft** \* [OneNote](https://www.fosslinux.com/20382/how-to-install-microsoft-onenote-on-linux.htm)

```
sudo npm install -g p3x-onenote --unsafe-perm=true --allow-root
```

13.
