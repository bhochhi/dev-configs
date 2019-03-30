Resources
---
* https://sourabhbajaj.com/mac-setup

zsh swag
----  
* https://medium.freecodecamp.org/jazz-up-your-zsh-terminal-in-seven-steps-a-visual-guide-e81a8fd59a38 
* prompt: https://github.com/denysdovhan/spaceship-prompt
* powerline-fonts: https://github.com/powerline/fonts




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
```alias j8="export JAVA_HOME=`/usr/libexec/java_home -v 1.8`; java -version"```  
```alias j11="export JAVA_HOME=`/usr/libexec/java_home -v 11`; java -version"``` . 


homebrew
---
| [Commands](https://devhints.io/homebrew)  |  Comments |
|---|---|
|brew install git  |	Install a package |
|brew upgrade git	 | Upgrade a package |
|brew unlink git	 | Unlink |
|brew link git	 | Link |
|brew switch git 2.5.0  |	Change versions  |
|brew list --versions git  |	See what versions you have|
|brew info git|	List versions, caveats, etc|
|brew cleanup git|	Remove old versions|
|brew edit git|	Edit this formula|
|brew cat git|	Print this formula|
|brew home git|	Open homepage|
|brew update	|Update brew and cask|
|brew list|	List installed|
|brew outdated	| What’s due for upgrades?|
|--|--|

