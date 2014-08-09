# Path to your oh-my-zsh configuration.
ZSH=$HOME/.oh-my-zsh

# Enable the access to the online help
unalias run-help
autoload run-help
HELPDIR=/usr/local/share/zsh/helpfiles

# Set name of the theme to load.
# Look in ~/.oh-my-zsh/themes/
# Optionally, if you set this to "random", it'll load a random theme each
# time that oh-my-zsh is loaded.
ZSH_THEME="gnzh"

# Set this to "true" to use case-sensitive completion.
CASE_SENSITIVE="false"

# Set this to "true" to disable bi-weekly auto-update checks.
DISABLE_AUTO_UPDATE="false"

# Set this to "true" if you want red dots to be displayed while waiting for completion
COMPLETION_WAITING_DOTS="true"

# Which plugins would you like to load? (plugins can be found in ~/.oh-my-zsh/plugins/*)
# Custom plugins may be added to ~/.oh-my-zsh/custom/plugins/
# Example format: plugins=(rails git textmate ruby lighthouse)
plugins=(autojump brew cabal cap celery coffee compleat cpanm dircycle encode64 fabric gem git gitfast git-extras git-flow git-hubflow gradle hub knife grails lain mercurial mvn nanoc node npm osx perl pip pow powify rails redis-cli ruby rvm sbt scala sublime tmux tmuxinator vagrant urltools virtualenvwrapper)
# TODO: Add bower and bundle when incompatibility gets resolved

source $ZSH/oh-my-zsh.sh

# RBEnv support
if which rbenv > /dev/null; then eval "$(rbenv init -)"; fi

# OpenNI support
if [ -d /usr/local/include/ni2 ]; then
  export OPENNI2_INCLUDE=/usr/local/include/ni2
fi
if [ -d /usr/local/lib/ni2 ]; then
  export OPENNI2_REDIST=/usr/local/lib/ni2
fi

export EDITOR=vim
