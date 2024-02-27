## 1.Install zsh 

```
brew install zsh
```

## 2.Make it default shell

```
command -v zsh | sudo tee -a /etc/shells
sudo chsh -s /bin/zsh
```

## 3.Install oh-my-zsh
```
sh -c "$(curl -fsSL https://raw.github.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"
```

## 4.Enable command highlighting 

```
brew install zsh-syntax-highlighting
echo "source $(brew --prefix)/share/zsh-syntax-highlighting/zsh-syntax-highlighting.zsh" >> ${ZDOTDIR:-$HOME}/.zshrc
source ~/.zshrc
```

## 5. Setup theme
 * Setup [Tomorrow Night Eighties theme](https://github.com/chriskempson/tomorrow-theme). 
 * Set background color to `#17161F`
 * Set opacity to `97%`
 * Set window size to `80x24`
 * Set font size to `14`
 * Use `Menlo regular` font
 * Install [pure propmpt](https://github.com/sindresorhus/pure)

 
