# Rahul Rawat's Dotfiles
---------------------------------------------------------------------------
A collection of the dotfiles used on my work and home Linux machines.

To use the dotfiles:
```bash
cd
git clone https://github.com/rahulraw/dotfiles.git
cd dotfiles 
./infectdots.sh
```

This install script does the following things: 
* Link .* (dotfiles) on your computer to this directory
* Initialize and update git submodules for pathogen plugins


To install YouCompleteMe:
```bash
cd ~/.vim/bundle/YouCompleteMe
./install.py --all
```
