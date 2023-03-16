#### For Ubuntu 22.04

- Stuff to install before tinkering the dotfiles and overall settings:
  - nvim (`https://github.com/neovim/neovim/releases/tag/stable`)
  - tmux (`sudo apt install tmux`)
  - lsd (https://github.com/Peltoche/lsd)
  - GoLang (`https://go.dev/doc/install`)

- Custom lsd settings
  - `mkdir ~/.config`
  - `mkdir ~/.config/lsd`
  - `cp ./.config/lsd/config.yml ~/.config/lsd/config.yaml`

- Custom Bash Terminal
  - `mv ~/.bashrc ~/.bashrc.bak`
  - `cp ./.bashrc ~/.bashrc`

- Customizing Tmux
  - Tmux Plugin Manager 
    - `git clone https://github.com/tmux-plugins/tpm ~/.tmux/plugins/tpm`
    - `cp ./.tmux.conf ~/.tmux.conf`
    - `tmux source ~/.tmux.conf`
    - `prefix` + `I`
  - Themes 'n' Stuff
    - `cp ./.tmux/plugins/tmux/catppuccin.tmux`
    - `cp ./.tmux/plugins/tmux/catppuccin-mocha.tmuxtheme`

- Customizing Nvim
  - Installing AstroVim
    - Follow installation instruction from `https://astronvim.com/`
  - Getting Up-to-date with my preferences
    - 
    
