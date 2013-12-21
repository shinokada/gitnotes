# Untracked files

While I was making [dotfiles](https://github.com/shinokada/dotfiles), I could not upload two directories, .oh-my-zsh and .zsh/zsh-syntax-highlighting. The reason was that they had .git folders. So I deleted .git and .gitignore. And cleared cache and add them all again.

    $ cd ~/dofiles/.oh-my-zsh
    $ rm -rf .git
    $ rm .gitignore
    $ cd ~/dofiles/.zsh/zsh-syntax-highlighting
    $ rm -rf .git
    $ rm .gitignore
    $ cd ~/dotfiles
    $ git rm -r --cached .
    $ git add .
    $ git commit -m "fixed untracked files"
