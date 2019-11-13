# Terminal Config
A reference for my general terminal setup.

This repository acts as a screenshot of my terminal configuration.

###### *NB: My development is on MacOS. Therefore several tools used are specific to MacOS, such as iTerm2.*

## Client
[iTerm2](https://iterm2.com/)

Profile is a slightly modified version of the default, with some application-specific modifications (such as triggers). Found in `iterm/Airy.json`.

## Shell
Zsh, using [Oh-my-zsh](https://github.com/robbyrussell/oh-my-zsh).
`rc/zshrc` is just a modified version of the `~/.zshrc` from _Oh-my-zsh_. 
Theme used for Zsh is [powerlevel10k](https://github.com/romkatv/powerlevel10k)
#### Installation
_Instruction from the github pages_
* Oh-my-zsh: `sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"`
* powerlevel10k: `git clone --depth=1 https://github.com/romkatv/powerlevel10k.git $ZSH_CUSTOM/themes/powerlevel10k`

## Aliases
Some aliases are bound to set tabs title and colors on iTerm. To use, the program `tabset` must be installed. It requires Node, and can be found on [npm::iterm2-tab-set](https://www.npmjs.com/package/iterm2-tab-set).

```
npm i -g iterm2-tab-set
```

## Vim
Found in `rc/vimrc`

Some notes:
* Spaces (4)
* Line numbers enabled
