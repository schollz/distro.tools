# distro.tools

This is a collection of shell scripts for easy management of your Linux install. The goal is to provide scripts for every possible use case from updating your system to configuring some special things. Feel free to provide your scripts.

## How to use it?

It's simple. Just type this into your terminal and replace `script` with the script to execute:

    curl -L distro.tools/script | sh

when the script doesn't need sudo, or

    sudo sh -c 'curl -L distro.tools/script | sh'

when the script needs sudo privileges.

## How to contribute

Just clone this repo and create a pull request. If I ([@jlelse](https://github.com/jlelse)) like it, I will accept it.

## Overview of scripts

### All

`install/telegram` (sudo) - Install Telegram *(requires wget, tar, /opt and /usr/local/bin)*

### Ubuntu

`ubuntu/update` (sudo) - Update your Ubuntu system including Snaps and Flatpaks