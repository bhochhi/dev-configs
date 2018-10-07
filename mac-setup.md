Resources
---
* https://sourabhbajaj.com/mac-setup


* Docker config


* Node js


Java
---
```sh
brew update
brew tap caskroom/versions 
brew cask install java  ==> install latest
brew cask install java8 

brew tap AdoptOpenJDK/openjdk  ==> for openjdk. 
brew install <version>  ==> find available version from https://github.com/AdoptOpenJDK/homebrew-openjdk  

/usr/libexec/java_home -V  ==> know what versions are installed and which one is current default.
export JAVA_HOME=`/usr/libexec/java_home -v 1.8` ==> to use 1.8 as default. add this export JAVA_HOME into shell init to make is persistance. 
```




