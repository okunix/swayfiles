# sway dotfiles

## deps

```bash
export PATH="$PATH:$HOME/.local/bin"

sudo pacman -S python sway swaybg swayidle swaylock xorg-xwayland xorg-xrdb grim slurp brightnessctl libpulse ttf-jetbrains-mono-nerd-font wmenu foot stow git

git clone --depth 1 https://github.com/okunix/swayfiles.git ~/.swayfiles

cd ~/.swayfiles

stow .
```
