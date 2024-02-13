# dotfiles
This repository contains my dotfiles for configuring my work environment.
The repo is structured in the same manner my important dotfiles are in my home directory, 
this way we can use GNU stow to automatically symlink to the same structure on a new 
system.


## Requirements
To automatically set up the dotfiles on a new system you will need GNU stow.
Run ```setup.sh``` from linux_setup repository to install relevant programmes.

## Instructions
go to home directory, clone this repository.
cd into the ~/dotfiles directory
run ```stow .```
