# My dotfile github experiment

I am leeching this from https://mjones44.medium.com/storing-dotfiles-in-a-git-repository-53f765c0005d

I did have to make a few edits to the config-init script to work with directory structures like `.config/hypr/config/file.conf`.

To get this started on new OS install, use 
```bash 
curl https://raw.githubusercontent.com/mknap/dotfiles/refs/heads/master/config-init | bash
```
## Usage

`config` is just an alias for `git` with some options, so to add a file:
```bash
config add file
config -m "commit message here"
config push
```
Or if you make edits to an already tracked file, 
```bash
config -am "commit message here"
config pus
h
```


To update a machine, use `config checkout`
`config pull` seemed to work.
`config fetch` didn't seem to do anything

Experimenting with branches, too, you can use `config checkout b branch` or `config switch branch` 

I want to rename the alias and config-init script to dotfile and dotfile-init
## Packages to install (pacman)

sudo pacman -S
vivaldi github-cli gnome-browser-connector
cpio meson cmake
yay
v4l2loopback-dkms
## some hyprland stuff:
sudo pacman -S hyprlauncher squeekboard

## Packages to install (yay)
yay -S 
tilem spotify-launcher visual-studio-code-bin zoom hyprpanel insync kando-git
ags-hyprpanel-git

## Packages to install (apt)
apt install tilem
