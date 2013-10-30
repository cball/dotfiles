##cball's dotfiles##

I manage my dotfiles using Homesick (http://github.com/technicalpickles/homesick).

###Install using Homesick###
```zsh
gem install homesick
homesick clone cball/dotfiles
homesick symlink dotfiles
```

###Install Vundle and Vim Bundles###
```zsh
git clone https://github.com/gmarik/vundle.git ~/.vim/bundle/vundle
vim -u ~/.vimrc.bundles +BundleInstall +qa
```

###Credits###
Thanks to thoughtbot and all the misc people along the way I stole this stuff from along the way.
