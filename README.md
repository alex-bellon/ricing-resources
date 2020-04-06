# Ricing Resources

## Apps

### Discord
- [Install BetterDiscord](https://gist.github.com/ObserverOfTime/d7e60eb9aa7fe837545c8cb77cf31172) to enable theming and custom CSS
- [Install Glasscord](https://github.com/AryToNeX/Glasscord) for transparent discord

### Spotify
- [Spicetify](https://github.com/khanhas/spicetify-cli) lets you customize colors
    - On Manjaro, be sure to run `sudo chmod -R 777 /opt/spotify` before running `spicetify backup apply enable-devtool`
    - Add new themes to `~/.config/spicetify/Themes/<name>` and change `current_theme = <name>` in `~/.config/spicetify/config.ini`

## Browser

### Firefox

- [userChrome.css](https://www.userchrome.org/)
  - [How to create a userChrome.css file](https://www.userchrome.org/how-create-userchrome-css.html)
  - [r/FirefoxCSS](https://www.reddit.com/r/FirefoxCSS/)
- [Pywalfox](https://github.com/Frewacom/Pywalfox) - sync `wal` colors to Firefox

## Dotfiles

- [Dotfiles on GitHub](https://dotfiles.github.io/)
- [Manage dotfiles with GNU `stow`](https://alexpearce.me/2016/02/managing-dotfiles-with-stow/)

## Editors
### `vim`

- [`vim`](https://github.com/vim/vim) - terminal based editor
- [Vundle](https://github.com/VundleVim/Vundle.vim) - plugin manager for `vim`
- `vim` plugins
  - [colorizer](https://github.com/lilydjwg/colorizer) - colorizes text in the form `#rrggbb` or `#rgb`
  - [ctrlp](https://github.com/ctrlpvim/ctrlp.vim) - fuzzy finder for `vim`
  - [goyo](https://github.com/junegunn/goyo.vim) - add margins on all sides of text to increase focus
  - [i3config](https://github.com/mboughaba/i3config.vim) - syntax highlighting for i3 config files
  - [nerdtree](https://github.com/scrooloose/nerdtree) - tree file explorer in `vim`
  - [syntastic](https://github.com/scrooloose/syntastic) - syntax checking plugin
  - [tabular](https://github.com/godlygeek/tabular) - text alignment tool
  - [vim-eunuch](https://github.com/tpope/vim-eunuch) - use UNIX commands from `vim`
  - [vim-illuminate](https://github.com/RRethy/vim-illuminate) - highlight all occurences of a word
  - [vim-markdown](https://github.com/plasticboy/vim-markdown) - syntax highlighting for Markdown
  - [vim-surround](https://github.com/tpope/vim-surround) - tools to help surround things with parentheses, quotes, tags, etc.
  - [wal](https://github.com/dylanaraps/wal.vim) - use `wal` colorscheme for `vim`
- [Vivify](http://bytefluent.com/vivify/) - Color scheme editor

## Terminal

### Programs

- neofetch
- [thefuck](https://github.com/nvbn/thefuck) - like autocorrect for terminal commands (also, you can change the keyword to something other than the f-bomb :smile:)

### `zsh`
- [oh-my-zsh](https://github.com/robbyrussell/oh-my-zsh) - Framework for the `zsh` shell that easily enables different themes and plugins
  - [Punctual theme](https://github.com/dannynimmo/punctual-zsh-theme)

- [`zsh` plugins](https://github.com/robbyrussell/oh-my-zsh/tree/master/plugins)
  - [colored-man-pages](https://github.com/robbyrussell/oh-my-zsh/tree/master/plugins/colored-man-pages) - Add color to the man pages
  - [fzf](https://github.com/robbyrussell/oh-my-zsh/tree/master/plugins/fzf) - Fuzzy finder, helps locate files, processes, commands, etc.
  - [git](https://github.com/robbyrussell/oh-my-zsh/tree/master/plugins/git) - Adds a lot of nice Git aliases and a few custom commands
  - [vi-mode](https://github.com/robbyrussell/oh-my-zsh/tree/master/plugins/vi-mode) - Use vi-like commands in `zsh`
  - [zsh-autosuggestions](https://github.com/zsh-users/zsh-autosuggestions) - Auto suggest commands based on history
  - [zsh-syntax-highlighting](https://github.com/zsh-users/zsh-syntax-highlighting) - Highlight syntax on the command line

## Theming

### `compton`

- Useful for adding blur/transparency, drop shadow, and more. 
    - See my [config](https://github.com/alex-bellon/dotfiles/blob/master/compton/.compton.conf) for more examples
- Use the `tryone` fork on AUR to get blur working. 

### GTK2/3

- Use [`lxappearance`](https://wiki.lxde.org/en/LXAppearance) and `gtk-chtheme` on i3. [Source](https://askubuntu.com/questions/598943/how-to-de-uglify-i3-wm)

### `wal`

- [Pywal](https://github.com/dylanaraps/pywal) - Tool that generates color schemes (for X, i3, etc.) from wallpapers
  - [Pywalfox](https://github.com/Frewacom/Pywalfox) - syncs `wal` color scheme to Firefox

### X

- You can edit `.Xdefaults`/`.Xresources` to change settings for X, most notably `urxvt` (in my case)

## Window Manager/Switcher

### `i3`

- [i3wm](https://i3wm.org/) - a tiling window manager
  - [i3gaps](https://github.com/Airblader/i3) - fork of i3 that allows gaps between windows
- [r/i3wm](https://www.reddit.com/r/i3wm/)

### `rofi`

- [rofi](https://github.com/davatorium/rofi) - minimal window switcher and program launcher
