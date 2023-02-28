# How to install

git clone --bare git@github.com:dkstrong/.dotfiles.git $HOME/.dotfiles

alias dotfiles='/usr/bin/git --git-dir=$HOME/.dotfiles --work-tree=$HOME'

dotfiles config --local status.showUntrackedFiles no

dotfiles checkout


will need to restart shell or manually source all of the files that were created/modified
