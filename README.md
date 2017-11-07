# Rahul Rawat's Dotfiles

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

To install xclip (allows your tmux buffer to sync with the system buffer):
```bash
sudo apt-get install --assume-yes xclip
```

To install YouCompleteMe:
```bash
cd ~/.vim/bundle/YouCompleteMe
./install.py --all
```
### Future Improvements
* Transition to Vundle from Pathogen
>> Pathogen way to version control utilized git submodules. Vundle requires 
plugin calls in your vimrc files which is a little more elegant.

* Transition to Antigen from Oh-my-zsh
>> Antigen is built with inspiration of oh-my-zsh and pathogen. However, it 
is tries to avoid the bloat of oh-my-zsh using Vundle inspired plugin calls.
