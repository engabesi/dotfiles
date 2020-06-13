# Installation
## Install prezto

```
git clone --recursive https://github.com/sorin-ionescu/prezto.git "${ZDOTDIR:-$HOME}/.zprezto"
```

```
setopt EXTENDED_GLOB
for rcfile in "${ZDOTDIR:-$HOME}"/.zprezto/runcoms/^README.md(.N); do
  ln -s "$rcfile" "${ZDOTDIR:-$HOME}/.${rcfile:t}"
done
```

.zshrc.old => .zshrc  
content copy & paste

## Install peco

```
brew install peco
```

## vimrc

font install for airline theme  
https://github.com/ryanoasis/nerd-fonts

```
ln -s ~/.vim/.vimrc ~/.vimrc
```

## nvm

```
export NVM_DIR="$HOME/.nvm" && (
  git clone https://github.com/nvm-sh/nvm.git "$NVM_DIR"
  cd "$NVM_DIR"
  git checkout `git describe --abbrev=0 --tags --match "v[0-9]*" $(git rev-list --tags --max-count=1)`
) && \. "$NVM_DIR/nvm.sh"
```

```:.bashrc
export NVM_DIR="$HOME/.nvm"
[ -s "$NVM_DIR/nvm.sh" ] && \. "$NVM_DIR/nvm.sh" # This loads nvm
```

# Documents

vim-Git  
https://github.com/tpope/vim-fugitive  
https://github.com/airblade/vim-gitgutter  
