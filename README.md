# hosted

1. ### Getting Started

Install zsh.

```
sudo apt install zsh
```

Install oh-my-zsh.

```
sh -c "$(wget https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh -O -)"
```

Set ZSH as default shell.

```
chsh -s $(which zsh)
```

2. ### *Optional*: Install P10K theme for ZSH.

Download the theme.

```
git clone --depth=1 https://github.com/romkatv/powerlevel10k.git ${ZSH_CUSTOM:-$HOME/.oh-my-zsh/custom}/themes/powerlevel10k
```
Set `ZSH_THEME="powerlevel10k/powerlevel10k"` in `~/.zshrc`.

Restart ZSH.

```
exec ZSH
```
Configure P10K theme to device specification.

3. ### Install scripts

Run this following in a ZSH terminal:

```
zsh -c "$(curl -fsSL https://raw.github.com/dawesry/hosted/main/gitscripts)"
```
