# gibo-fzf

Use gibo interactively.

## Deprecated

I recommend `generate` `generate-gitignore` instead.

https://generate.github.io/generate/

```zsh
npm install -g generate generate-gitignore
```

Installation by `yarn` didn't work, I don't know why.

## Requirements

* [fzf](https://github.com/junegunn/fzf)
* [gibo](https://github.com/simonwhitaker/gibo)

## Installation

```zsh
zplug 'sei40kr/gibo-fzf', as:command, lazy:true
```

## Usage

Execute `gibo-fzf` to start generating .gitignore interactively.

```sh
gibo-fzf
```

You can choose multiple items, use Tab key to select and Enter to generate.
