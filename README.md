# ohmyzsh-theme-passion

An oh-my-zsh theme.

## Introduction

![passion](https://raw.githubusercontent.com/ChesterYue/ohmyzsh-theme-passion/master/passion.gif)

* real time prompt.
* command running time cost prompt.
* command running error hint.

## Installation

```bash
get -O ~/.oh-my-zsh/custom/themes/passion.zsh-theme https://raw.githubusercontent.com/aljeshishe/ohmyzsh-theme-passion/master/passion.zsh-theme
```

add to ~/.zshrc
```
ZSH_THEME="passion"
# optional
export PASSION_BEEP_THRESHOLD=5
```

REF: [Oh-My-Zsh External themes](https://github.com/ohmyzsh/ohmyzsh/wiki/External-themes)

## Trouble Shooting

### macOS

passion.zsh-theme depends on cmd ```gdate``` to get current time in milliseconds which is not installed by default in macOS.

to get ```gdate``` by running ```brew install coreutils;```
