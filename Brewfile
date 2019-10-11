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

brew tap homebrew/core
brew install adns
brew install autoconf
brew install automake
brew install boost
brew install cgal
brew install coreutils
brew install cscope
brew install eigen
brew install freexl
brew install gdbm
brew install geos
brew install gettext
brew install giflib
brew install git
brew install gmp
brew install gnupg
brew install gnutls
brew install go
brew install icu4c
brew install jpeg
brew install json-c
brew install libassuan
brew install libevent
brew install libffi
brew install libgcrypt
brew install libgeotiff
brew install libgpg-error
brew install libidn2
brew install libksba
brew install libpng
brew install libpq
brew install libspatialite
brew install libssh
brew install libtasn1
brew install libtiff
brew install libtool
brew install libunistring
brew install libusb
brew install libxml2
brew install libyaml
brew install lua
brew install macvim
brew install mas
brew install md5deep
brew install mpfr
brew install msgpack
brew install nettle
brew install node
brew install npth
brew install openssl
brew install openssl@1.1
brew install p11-kit
brew install pcre
brew install pcre2
brew install pinentry
brew install pkg-config
brew install postgresql
brew install proj
brew install pyenv
brew install python
brew install python@2
brew install readline
brew install ruby
brew install sfcgal
brew install sqlite
brew install swiftlint
brew install tmate
brew install unbound
brew install wget
brew install xctool
brew install xz

brew tap homebrew/cask
brew cask install firefox

brew tap rcmdnk/file
brew install brew-file

brew tap rcmdnk/mytest
brew install mytest2 --HEAD

# Other pip packages
brew pip django

# Other Cask applications
brew cask install xquartz

# Other commands
echo before
echo other commands
echo after
