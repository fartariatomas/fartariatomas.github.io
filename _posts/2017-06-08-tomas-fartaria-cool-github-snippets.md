---
layout: post
title: "Useful code snippets"
date: 2017-06-08
---

* Enable autocorrect:

  `git config --global help.autocorrect 1`
* Add a dad joke when you misspell `git add` (seen [here](https://www.reddit.com/r/git/comments/6ecr4o/git_dad/)):

  `git config --global alias.dad '!curl https://icanhazdadjoke.com/ && git add'`
* Add to .bash_profile to have git completion (probably still have to install it with brew or equivalent):
    
    ```\# to activate bash-autocomplete
    if [ -f $(brew --prefix)/etc/bash_completion ]; then
   . $(brew --prefix)/etc/bash_completion
   fi
  
   if [ -f ~/.git-completion.bash ]; then
   . ~/.git-completion.bash
   . ~/.git_shell
   fi
   ```
* will add more here when I find or remember some more