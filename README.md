# Ruby Environment setup

1.Install Homebrew - https://brew.sh/

$ /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install.sh)"


2.Install oh-my-zsh (optional) - https://ohmyz.sh/

$ sh -c "$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"


3.Install zsh git (optional) - https://github.com/ohmyzsh/ohmyzsh/blob/master/plugins/git/git.plugin.zsh

$ brew install zsh-git-prompt


4.Install rbenv - https://github.com/rbenv/rbenv

$ brew install rbenv ruby-build rbenv-vars


5.Install the latest version of Ruby

$ rbenv install --list
$ rbenv install 2.7.2 # In the book, it was 2.7.1, but need to use 2.7.2 for M1 chip Mac
$ rbenv local 2.7.2
