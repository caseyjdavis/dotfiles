# This repo is part of my larger WSL setup documented in this repository

https://github.com/caseyjdavis/setup

All terminal requirements are installed using the setup repo, but if you are just cloning this repo you can manually install by using the instructions below.

## Manual Installation Instructions Only

## Install oh-my-zsh
```
sh -c "$(wget https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh -O -)"
```

## Install powerlevel10k
```
git clone --depth=1 https://github.com/romkatv/powerlevel10k.git ${ZSH_CUSTOM:-$HOME/.oh-my-zsh/custom}/themes/powerlevel10k
```

## Install gruvbox theme
```
curl -L https://raw.githubusercontent.com/sbugzu/gruvbox-zsh/master/gruvbox.zsh-theme > ~/.oh-my-zsh/custom/themes/gruvbox.zsh-theme
```
