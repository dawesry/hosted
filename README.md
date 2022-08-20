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

Use `p10k configure` to configure to device specification.

```
Settings:
---
Prompt Style: 3. Rainbow
Character Set: 1. Unicode
Show Time: 1. No
Prompt Separators: 3. Slanted
Prompt Heads: 1. Sharp
Prompt Tails: 1. Flat
Prompt Height: 1. One Line
Prompt Spacing: 2. Sparse
Icons: 2. Many Icons
Prompt Flow: 1. Consise
Transient Prompt: y. Yes

Rest of settings: Set to preference.
```
Set GNOME Theme to Atom One Dark with:
`bash -c "$(curl -fsSL https://raw.githubusercontent.com/denysdovhan/gnome-terminal-one/master/one-dark.sh)"`



3. ### Install scripts

Run this following in a ZSH terminal:

```
zsh -c "$(curl -fsSL https://raw.github.com/dawesry/hosted/main/gitscripts)"
```
