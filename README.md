1. ### Getting Started

### Pre-Install
Run this following in a BASH terminal to install ZSH & themes, and Git:

```
bash -c "$(curl -fsSL https://raw.github.com/dawesry/hosted/main/bin/sys/inszsh)"
```

Run this following in a BASH terminal to install Docker:

```
bash -c "$(curl -fsSL https://raw.github.com/dawesry/hosted/main/bin/sys/insdocker)"
```

### Pull `~/bin` Directory
Run this following in a ZSH terminal for a first time pull:

```
zsh -c "$(curl -fsSL https://raw.github.com/dawesry/hosted/main/pullbin)"
```


## Script Usage

| Script Command | Usage |
|---	|---	|
| `upscript` | update scripts in ~/bin |
| `zshconup` | update p10k configuration |
| `scriptperm` | update executable permissions for ~/bin |
| `nascon` | mount NFS share |
| `cleanup` | remove *.old directories |
| `packup` | update machine packages |
| `pulldockcomp` | pull latest docker-compose.yml |
| `*clientname` | SSH connect to specified client |

