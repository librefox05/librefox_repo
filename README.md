# Librefox

This is a customized firefox project which includes different preferences that respect user privacy as much as possible. We use preferences from betterfox and cachyOS.

## Usage
To use librefox builds, add this repo in pacman by pasting the following

```
[librefox_repo]
SigLevel = Optional DatabaseOptional
Server = https://github.com/librefox05/$repo/raw/refs/heads/main/$arch
```

then run
```
sudo pacman -Syy firefox-stable-bin
```


