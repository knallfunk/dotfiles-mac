dotfiles
========

I spend way too much time customizing vim/bash/terminal/younameit.

### Vim

Here's how my MacVim window looks:

![MacVim+Solarized+Powerline+CtrlP](https://raw.github.com/milkbikis/dotfiles-mac/master/vim-screenshot.png)

### Bash

**Update:** Moved the powerline-bash script to its own [repository](https://github.com/milkbikis/powerline-bash) 

I implemented a [Powerline](https://github.com/Lokaltog/vim-powerline) like prompt for Bash:

![MacVim+Solarized+Powerline+CtrlP](https://raw.github.com/milkbikis/dotfiles-mac/master/bash-powerline-screenshot.png)

*  Displays the current git branch
*  Changes color if the last command exited with a failure code
*  If you're too deep into a directory tree, shortens the displayed path with an ellipsis
*  It's all done in a Python script, so you could go nuts with it

The .bashrc also has a handy function for adding bash aliases for git commands, without losing bash completion:

![MacVim+Solarized+Powerline+CtrlP](https://raw.github.com/milkbikis/dotfiles-mac/master/git-aliases-screenshot.png)

*  Make the vi command open files in a single MacVim window
