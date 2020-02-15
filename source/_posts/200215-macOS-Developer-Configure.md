---
title: macOS Developer Tools Install And Configure
date: 2020-02-15 20:32:02
tags:
- macOS
---

# Tools

## iTem2

`Github`：https://github.com/gnachman/iTerm2

## Homebrew

`官网`：https://brew.sh/

`Install`：

```shell
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```

## Zsh

`Github`：https://github.com/zsh-users/zsh

`Change Shell`：

```shell
chsh -s /bin/zsh
```

## Oh My Zsh

`Github`：https://github.com/ohmyzsh/ohmyzsh

`Install`：

```shell
sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```

`Add Plugin`：

```shell
vim ~/.zshrc

ZSH_THEME="ys"

plugins=(
        git
        zsh-syntax-highlighting
        zsh-autosuggestions
)
```

`zsh-syntax-highlighting`：

```shell
git clone https://github.com/zsh-users/zsh-syntax-highlighting.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-syntax-highlighting
```

`zsh-autosuggestions`：

```shell
git clone https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions
```

## nvm

`Github`：https://github.com/nvm-sh/nvm

```shell
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.35.2/install.sh | bash
```

# Software

| Name   | Link                   | Description |
| ------ | ---------------------- | ----------- |
| Typora | https://www.typora.io/ | Markdown    |

