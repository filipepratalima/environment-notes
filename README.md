# environment-notes
Collection of stuff and configs I currently like in my war chest. Though install notes are mostly for MacOS, I like to use MacOS/Linux cross-compatible tools.

## Terminal
### iterm2
* https://www.iterm2.com/
* Themes: https://iterm2colorschemes.com/
  * https://raw.githubusercontent.com/mbadolato/iTerm2-Color-Schemes/master/schemes/Misterioso.itermcolors
  * https://raw.githubusercontent.com/mbadolato/iTerm2-Color-Schemes/master/schemes/Obsidian.itermcolors
  * https://raw.githubusercontent.com/mbadolato/iTerm2-Color-Schemes/master/schemes/Cobalt2.itermcolors
  * https://raw.githubusercontent.com/mbadolato/iTerm2-Color-Schemes/master/schemes/Darkside.itermcolors
### Alacritty
* https://github.com/alacritty/alacritty
* config:
  * https://raw.githubusercontent.com/alacritty/alacritty/master/alacritty.yml
* Themes: https://github.com/eendroroy/alacritty-theme
  * https://github.com/eendroroy/alacritty-theme/blob/master/themes/gruvbox_dark.yaml
  * https://github.com/eendroroy/alacritty-theme/blob/master/themes/material_theme.yaml
  * https://github.com/eendroroy/alacritty-theme/blob/master/themes/dracula.yaml
```sh
brew cask install alacritty
```

## Shell
### oh-my-zsh
* https://github.com/ohmyzsh/ohmyzsh
```sh
sh -c "$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```
### Addons
* fzf
  * https://github.com/junegunn/fzf
  * https://github.com/changyuheng/zsh-interactive-cd

## Package management
### Homebrew
* https://brew.sh/
```sh
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install.sh)"
```

## Development
### Node Version Manager
* https://github.com/nvm-sh/nvm
```sh
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.35.3/install.sh | bash
```
### Deno
* https://deno.land/
```sh
curl -fsSL https://deno.land/x/install/install.sh | sh
```
```sh
brew install deno
```

## Others Stuff
### Font
* Firacode (with ligature)
  * https://github.com/tonsky/FiraCode

### ZeroTier
* https://www.zerotier.com/
```sh
curl -s https://install.zerotier.com | sudo bash
```

### screenfetch
* https://github.com/KittyKatt/screenFetch
```sh
brew install screenfetch
```
### dust (du in rust)
* https://github.com/bootandy/dust
```sh
brew install dust
```
### ripgrep (grep'ish in rust)
* https://github.com/BurntSushi/ripgrep/blob/master/GUIDE.md
```sh
brew install ripgrep
```
