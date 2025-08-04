# CachyOS install
My CachyOS install repository - All software &amp; tweaks

- [CachyOS install](#cachyos-install)
  - [Software](#software)
    - [Basic](#basic)
      - [Terminal](#terminal)
      - [File search (indexed)](#file-search-indexed)
      - [Google Drive sync](#google-drive-sync)
      - [Backup \& Restore](#backup--restore)
    - [Gaming](#gaming)
      - [RuneScape](#runescape)
      - [Battle.net / World of Warcraft](#battlenet--world-of-warcraft)
        - [World of Warcraft](#world-of-warcraft)
    - [Photo editing](#photo-editing)
    - [Image viewer](#image-viewer)
      - [nomacs](#nomacs)
    - [Music](#music)
      - [Player](#player)
      - [EQ](#eq)
        - [software](#software-1)
        - [profiles](#profiles)
    - [Remote Desktop to Windows](#remote-desktop-to-windows)


## Software
### Basic
#### Terminal
- Ghostty
```
paru ghostty
```

#### File search (indexed)
- FSearch

#### Google Drive sync
[Insync](https://www.insynchq.com/) - Support for multiple Cloud integrations and adds CLI support for uploading/downloading files.
```
sudo pacman -S insync insync-dolphin
```

#### Backup & Restore
- Veeam > Root disk image level backup
- Borg + Vorta for Borg > File backup

### Gaming
- Bottles
- Steam
- Lutris

#### RuneScape
- Bolt
```
paru bolt-launcher
```
- Runescape Game Client (NXT)
```
paru runescape-launcher
```
- Runelite
```
paru runelite
```

#### Battle.net / World of Warcraft
- Faugus Launcher
- Default Proton: GE-Proton Latest (default)
```
paru faugus-launcher
```

##### World of Warcraft
- CurseForge Beta for Linux

### Photo editing
- RawTherapee
- Darktable

### Image viewer
#### [nomacs](https://github.com/nomacs/nomacs)
```
paru nomacs-qt6-git
```

### Music
#### Player
- Celementine

#### EQ
##### software
- Easy Effects (for profiles per headphone)
```
paru easyeffects
```
##### profiles
[AutoEQ](https://autoeq.app/)

### Remote Desktop to Windows
- Remmina
- Remmina plugins for rdesktop, ultravnc