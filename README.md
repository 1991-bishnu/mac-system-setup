# Mac-System-Setup
Mac System Setup

## Install Xcode
 - Might need to upgrade the OS version


## Install homebrew

`/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"`

`echo >> /Users/bishnu/.zprofile`
`echo 'eval "$(/opt/homebrew/bin/brew shellenv)"' >> /Users/bishnu/.zprofile`
`eval "$(/opt/homebrew/bin/brew shellenv)"`

`brew —version`


## Install VS code
 
`brew install --cask visual-studio-code`

## Install GIT

`brew install git`
git username setup


## Install python

`brew install python`
`export PATH="/usr/local/opt/python@3.12/bin:$PATH"`
`python3 --version`


## Install GO

`brew install go`
`go version`
`export GOPATH=$HOME/go``
`export PATH=$PATH:$GOPATH/bin``

## Install PHP

`brew install php`
`php -v`

## Install Node

`brew install node`
`node --version`
`npm --version`

## Install docker

`brew install --cask docker`
`docker --version`

## Install podmam(substitute of docker)

`brew install podman-desktop`
`podman version`

## Install Oh my Zsh(Optional)

`sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"`
