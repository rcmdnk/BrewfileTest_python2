#!/usr/bin/env bash

#BREWFILE_IGNORE
if ! which brew >& /dev/null;then
  brew_installed=0
  echo Homebrew is not installed!
  echo Install now...
  echo ruby -e \"\$\(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install\)\"
  ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
  echo
fi
#BREWFILE_ENDIGNORE

# tap repositories and their packages

brew tap caskroom/cask
brew cask install iterm2
brew cask install java
brew cask install oclint
brew cask install rubymotion
brew cask install xquartz

brew tap homebrew/core
brew install sqlite
brew install libassuan
brew install adns
brew install pth
brew install json-c
brew install libxml2
brew install libtiff
brew install msgpack
brew install jpeg
brew install libksba
brew install libspatialite
brew install go
brew install swiftlint
brew install libgpg-error
brew install openssl@1.1
brew install macvim --without-python
brew install freexl
brew install gdbm
brew install libssh
brew install libusb-compat
brew install pcre
brew install git
brew install brew-gem
brew install libunistring
brew install carthage
brew install geos
brew install wget
brew install gettext
brew install automake
brew install brew-pip
brew install coreutils
brew install xctool
brew install libpng
brew install gmp
brew install boost
brew install md5deep
brew install gpg-agent
brew install node
brew install mas
brew install giflib
brew install tmate
brew install python
brew install cgal
brew install pinentry
brew install maven
brew install libusb
brew install libtool
brew install tmux
brew install libevent
brew install libffi
brew install gnutls
brew install readline
brew install liblwgeom
brew install libgeotiff
brew install libgcrypt
brew install gdal
brew install dirmngr
brew install pyenv
brew install npth
brew install autoconf
brew install postgresql
brew install p11-kit
brew install lzlib
brew install libyaml
brew install sfcgal
brew install mercurial
brew install pkg-config
brew install libtasn1
brew install openssl
brew install postgis
brew install icu4c
brew install nettle
brew install proj
brew install gnupg
brew install cscope
brew install mpfr

brew tap homebrew/dupes

brew tap rcmdnk/file
brew install brew-file

brew tap rcmdnk/mytest
brew install mytest2 --HEAD

brew tap rcmdnk/rcmdnkcask
brew cask install font-migu1m

brew tap rcmdnk/rcmdnkpac

# pip packages
brew pip django
brew pip gcalcli

# gem packages
brew gem install heroku

# Other commands
echo before
echo other commands
echo after
