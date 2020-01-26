# Middleclick
Install Middleclick utility and change it to use four fingers.
Be sure to add Middleclick to System Prefs > Security & Privacy > Accessibility
```bash
brew cask install middleclick
defaults write com.rouge41.middleClick fingers 4
```

# ZSH
Machine specific zsh settings can be added to `~/.custom.zshrc`
```bash
brew install zsh
sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"
ln -s path/to/this/.zshrc ~/.zshrc
```
