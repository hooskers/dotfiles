# iterm2
iterm2 > Install Shell Integration

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

git clone https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions

git clone https://github.com/zsh-users/zsh-syntax-highlighting.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-syntax-highlighting

git clone https://github.com/denysdovhan/spaceship-prompt.git "$ZSH_CUSTOM/themes/spaceship-prompt"
ln -s "$ZSH_CUSTOM/themes/spaceship-prompt/spaceship.zsh-theme" "$ZSH_CUSTOM/themes/spaceship.zsh-theme"

ln -s path/to/this/.zshrc ~/.zshrc
```

# thefuck
```bash
brew install thefuck
```

# nodenv
```bash
brew install nodenv
```
