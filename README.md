# dotfiles
## What is this?
- This repo contains my common configuration files for Bash, i3wm, polybar, rofi, etc. and some utility scripts.
- Intention is to clone it, and configure things quickly when I move to a new environment.
- Feel free to use any of these things.
## How does it work?
- Each folder contains some configuration files. You can copy them to their respective directories.
- You can also use `copy.sh` script to copy files *into* this repository.
- Make the `copy.sh` executable first before you use it:
```bash
chmod +x ./copy.sh
./copy.sh
```
- This script will copy config files (override whatever is in this repo).