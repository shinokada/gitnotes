# Git and Vim

Reference: [Using Git from command-line mode](http://www.slideshare.net/cohama/how-to-use-git-from-vim-vim-conf2013)

## Set core.editor

    git config --global core.editor vim
    # check your config
    git config --list

## Using Git from command line

    # use :!
    # add the current file
    :!git add %
    :!git commit -m "commit message"
    :!git push origin master
    :!git diff --cached

## Adding key mapping

    nnoremap \ga :<C-u>!git add  %<CR>
