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
config -am "commit message here"
config push
```

To update a machine, use `config checkout` (or `config fetch` ? or `config pull` ?)

Experimenting with branches, too, you can use `config checkout b branch` or `config switch branch` 

I want to rename the alias and config-init script to dotfile and dotfile-init
## Packages to install (pacman)

sudo pacman -S vivaldi github-cli

## Packages to install (yay)
yay -S tilem2

## Packages to install (apt)
