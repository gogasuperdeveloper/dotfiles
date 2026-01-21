#Owner: Lazariev Heorhii

#Info: Repository contains configuration files.

#Requirements:
  - zsh
  - git

#Install:
  - git clone --bare git@github.com:gogasuperdeveloper/dotfiles.git $HOME/.dotfiles

  - alias dotfiles='git --git-dir=$HOME/.dotfiles --work-tree=$HOME'

  - dotfiles checkout

  - dotfiles config --local status.showUntrackedFiles no

  - exec zsh

#Included_files:
  - .zshrc
  - .p10k.zsh


