# dotfiles
yadm repo of my dotfiles

## Install applications
```
sudo apt install vim tmux zsh mc
```

## Install oh-my-zsh
```
sh -c "$(wget https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh -O -)"
```

## Install Starship
```
curl -sS https://starship.rs/install.sh | sh
```

## Install powerlevel10k
```
git clone --depth=1 https://github.com/romkatv/powerlevel10k.git ${ZSH_CUSTOM:-$HOME/.oh-my-zsh/custom}/themes/powerlevel10k
```
