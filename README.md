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

## Usage


Run this following in a ZSH terminal for a full install:

```
zsh -c "$(curl -fsSL https://raw.github.com/dawesry/hosted/main/fullinstall)"
```

| Script Command | Usage |
|---	|---	|
| `upscript` | update scripts in ~/bin |
| `zshconup` | update p10k configuration |
| `scriptperm` | update executable permissions for ~/bin |
| `nascon` | mount NFS share |
| `cleanup` | remove *.old directories |
| `packup` | update machine packages |
| `*clientname` | SSH connect to specified client |

