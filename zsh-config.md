# Zsh Config

Starting point for getting Zsh set up on a new machine tailored to my liking.

Assuming a mac with Zsh already the default terminal.

- Install [iTerm2](https://iterm2.com/)
- Download [iTerm2 color themes](https://github.com/mbadolato/iterm2-color-schemes#installation-instructions) (can do it from here too where there are screenshots [Iterm2-color-schemes](https://iterm2colorschemes.com/))
- Install [Oh My Zsh](https://github.com/ohmyzsh/ohmyzsh)
  - This should generate a `~/.zshrc`


## `.zshrc` Settings I Like

```sh
ZSH_THEME="awesomepanda"

# --- Aliases ----
# Show hidden files in ls
alias ls='ls -A'

# Git aliases
alias gcm="git commit -m"
alias gcb="git checkout -b"
# Undo last commit but keep changes
alias gundo="git reset --soft HEAD~1"
# Add staged files to last commit, no new message
alias gfix="git commit --amend --no-edit"
# Abort merge
alias gabort="git merge --abort"

```
