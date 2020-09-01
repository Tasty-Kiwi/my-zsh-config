# My Zsh Config.

To install it: type: `git clone https://github.com/PapuasinisPingvinas/my-zsh-config.git`;

`cp my-zsh-config/.zshrc ~/.zshrc`.

You need to to install zsh-autosuggestions, so type: `git clone https://github.com/zsh-users/zsh-autosuggestions ~/.zsh/zsh-autosuggestions`

You need to to install zsh-syntax-highlighting, so type:`git clone https://github.com/zsh-users/zsh-syntax-highlighting.git`;

#### NOW FOR THE NEXT COMMAND YOU NEED TO USE ZSH FOR THAT!

`echo "source ${(q-)PWD}/zsh-syntax-highlighting/zsh-syntax-highlighting.zsh" >> ${ZDOTDIR:-$HOME}/.zshrc`.

You need to install pure-shell, so tpye: `mkdir -p "$HOME/.zsh"`; `git clone https://github.com/sindresorhus/pure.git "$HOME/.zsh/pure"`.

The source lines are already present in the .zshrc.

### Made by PapuasinisPingvinas, and under the MIT license.
