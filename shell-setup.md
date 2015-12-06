## 1.Install zsh 

```
brew install zsh
```

## 2.Make it default shell

```
command -v zsh | sudo tee -a /etc/shells
sudo chsh -s /usr/local/bin/zsh
```

## 3.Enable command highlighting 

```
brew install zsh-syntax-highlighting
echo "source /usr/local/share/zsh-syntax-highlighting/zsh-syntax-highlighting.zsh" >> ~/.zshrc
source ~/.zshrc
```

## 4. Setup theme
 * Setup [Tomorrow Night Eighties theme](https://github.com/chriskempson/tomorrow-theme). 
 * Set background color to `#17161F`
 * Set window size to `80x24`
 * Set font size to `14`
 * Install [pure propmpt](https://github.com/sindresorhus/pure)

 
