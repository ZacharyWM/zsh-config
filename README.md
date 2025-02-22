# Full setup

## install ohmyzsh
```bash
sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```

## install fonts
```bash
### clone 
git clone https://github.com/powerline/fonts.git --depth=1
### install
cd fonts
./install.sh
### clean-up a bit
cd ..
rm -rf fonts
```

## install plugins
```bash
git clone https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions
```
```bash
git clone https://github.com/zsh-users/zsh-syntax-highlighting.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-syntax-highlighting
```