## Shell
---

### A Better Shell - Zsh

Zsh offers a better shell experience with extensions that provide extra functinality like themes, colors, highlights ahd more. 

1. Install oh-my-zsh [here](https://ohmyz.sh/)
1. Open terminal
1. Set zsh as the default shell - `chsh -s $(which zsh)`

These are my preferred custom extensions.

| Extension | Install | Notes |
| -- | -- | -- |
| zsh-syntax-highlighting | brew install zsh-syntax-highlighting | Highlights whether the commands are correct |
| zsh-autosuggestions | brew install zsh-autosuggestions | Auto suggests command completion based on history |

##### Troubleshooting

- When installing zsh - your shell will reference `~/.zshrc` - this file should source your ~/.bash_profile so you can still add your custom environment configuration there.

### Useful ~/.bash_profile

These are the most commonly used environment configurations I use. Most of them to shortcut commands.

| Description | Command |
| -- | -- |
| List directory with permissions | `alias ll='ls -l'` |
| Show my bash_profile | `alias env='cat ~/.bash_profile'` |
| Edit my bash_profile | `alias envedit='vi ~/.bash_profile'` |
| Refresh my bash_profile | `alias envref='source ~/.bash_profile'` |
| Open application with parameter | `alias code='open -a Visual\ Studio\ Code.app'` |
