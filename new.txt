#! /bin/bash

# This code block installs sublime text. 

sudo apt update
sudo apt-get install curl -y
sudo apt install dirmngr gnupg apt-transport-https ca-certificates software-properties-common
curl -fsSL https://download.sublimetext.com/sublimehq-pub.gpg | sudo apt-key add -
sudo add-apt-repository deb https://download.sublimetext.com/ apt/stable/
sudo apt install sublime-text

# This code block installs VIM Editor

sudo apt install vim -y
