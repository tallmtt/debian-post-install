# Matt's new rice void (Built upon Randi's)

## Todo

- [ ] Mutt wizard
  - https://github.com/LukeSmithxyz/mutt-wizard

---

NOTE: This is in progress - use at your own risk!

Setup my default install (practice on virtualbox)

Install [debian os](https://cdimage.debian.org/cdimage/unofficial/non-free/cd-including-firmware/current/amd64/iso-cd/)

Debian 11 version (code name "bullseye")

---

My setup is install debian minimal without GUI and used expert method.

```bash
$ sudo apt install git

$ git clone https://github.com/tallmtt/debian-post-install.git

$ cd debian-dwm

$ ./install.sh
```

Finish the setup
```bash
$ sudo reboot
```
That's it.

## Installs and sets up:

- File Manager: Ranger
- ls replaced with exa
  - [ ] bashrc edits (add >> aliases for ls)
- [ ] microcode (intel or amd)
- Display Manager: LightDM
- Window Manager: dwm
- Terminal: st
- Menu: dmenu
- Browser: Firefox 
- Image browser: feh or nitrogen
- neofetch 
- htop

## Add to this:

- emacs
- wireguard
- joplin
  - Script to download/update
  - Make quick script to run joplin appimage with "--no-sandbox" option
  - sudo ln -s /usr/local/android-studio/bin/studio.sh /usr/bin/android-studio
- Virtualbox
  - https://www.virtualbox.org/wiki/Linux_Downloads
  - Download both .deb and guest cd
  - sudo apt install ./file.deb
- gimp
- picom
- pandoc
- neomutt
- PCmanFM - File manager
- keepassxc
- nextcloud-desktop
- Video and Audio Tools
  - ffmpeg
  - vlc
  - cmus (cli audio player)
  - qmmp (simple mp3 player)
  - lmms (digtal audio workstation)
  - flowblade
  - audacity
  - easytag
- network-manager
- LibreOffice
- hledger
- imagemagick
- python stuff (using pipx):
  - pywal
    - sudo apt install python3-pip python3-venv
    - python3 -m pip install --user pipx
    - pipx ensurepath
    - pipx install pywal
  - lektor
    - pipx install lektor
  - jupyter-notebook
    - pipx install notebook
  - grip (for emacs)
    - python3 -m pip install grip

### Include

- configs for dwm, st, dmenu, autostart, neomutt, wireguard
    - git for configs
    - set up symlinks for what are needed
- Wallpaper images
    - git for my walls
    - ibis.jpg
