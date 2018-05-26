# sublime configuration
## Sublime: pros and cons
### Pros
* It is a really fast editor.
* It is pretty customisable.
* Pretty well configured out of the box.

### Cons
* customisation is too distributed.

## Packages
* Terminal view.
* Side bar enhancements.

## General Key bindings

## install instructions

1. install sublime
	* arch based:
		1. curl -O https://download.sublimetext.com/sublimehq-pub.gpg && sudo pacman-key --add sublimehq-pub.gpg && sudo pacman-key --lsign-key 8A8F901A && rm sublimehq-pub.gpg
		2. echo -e "\n[sublime-text]\nServer = https://download.sublimetext.com/arch/stable/x86_64" | sudo tee -a /etc/pacman.conf
		3. sudo pacman -Syu sublime-text
	* debian based:
		1. wget -qO - https://download.sublimetext.com/sublimehq-pub.gpg | sudo apt-key add -
		2. sudo apt-get install apt-transport-https
		3. echo "deb https://download.sublimetext.com/ apt/stable/" | sudo tee /etc/apt/sources.list.d/sublime-text.list
		4. sudo apt-get update
		5. sudo apt-get install sublime-text
2. install package control
	* C-S-p install package control
3. install packages
	* C-S-p install package ...

