[adriablade] dotfiles ![Bower](https://img.shields.io/badge/dotfiles-in_progress-red.svg)
==========================

Setup
-----

To set up the `dotfiles` run the appropriate snippet in the terminal:

(⚠️  **DO NOT** run the `setup` snippet if you do not fully understand
[what it does][setup]. Seriously, **DON'T**!)

| OS | Snippet |
|:---|:---|
| `macOS` | `bash -c "$(curl -LsS https://raw.github.com/adrianblade/dotfiles/master/os/bootstrap.sh)"` |
| `Ubuntu` | `bash -c "$(wget -qO - https://raw.github.com/adrianblade/dotfiles/master/os/bootstrap.sh)"` |

```
1.- create_directories.sh - Create custom directories
2.- create_symbolic_links.sh - Create files
  "shell/aliases/bash_aliases"
        "shell/autocomplete/$(get_os)/bash_autocomplete"
        "shell/bash_exports"
        "shell/bash_functions"
        "shell/bash_logout"
        "shell/bash_options"
        "shell/bash_profile"
        "shell/bash_prompt"
        "shell/bashrc"
        "shell/curlrc"
        "shell/inputrc"
        "git/gitattributes"
        "git/gitconfig"
        "git/gitignore"
        "git/gitmodules"
        "tmux/tmux.conf"
        "vim/vim"
        "vim/vimrc"
3.- create_local_config_files.sh
      Create bash.config.local
      Create git.config.local
      Create vim.config.local
4.- install/main.sh
      Install Chrome
      Install Curl
      Install Firefox
      Install Git
      Install Gimp
      Install npm
      Install Shellcheck
      Install tmux
      Install vim
      Install vlc
      Install xclip
5.- preferences/main.sh
      Terminal configuration
      Keyborard configuration
6.- restart.sh  - Restart pc
```
