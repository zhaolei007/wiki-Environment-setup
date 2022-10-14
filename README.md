# Ruby Environment setup
Install Homebrew - https://brew.sh/
$ /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install.sh)"
Install oh-my-zsh (optional) - https://ohmyz.sh/
$ sh -c "$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
Install zsh git (optional) - https://github.com/ohmyzsh/ohmyzsh/blob/master/plugins/git/git.plugin.zsh
$ brew install zsh-git-prompt
Install rbenv - https://github.com/rbenv/rbenv
$ brew install rbenv ruby-build rbenv-vars
Install the latest version of Ruby
$ rbenv install --list
$ rbenv install 2.7.2 # In the book, it was 2.7.1, but need to use 2.7.2 for M1 chip Mac
$ rbenv local 2.7.2
