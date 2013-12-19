# gitignore notes

## Adding gitignore file after git init

Remove the files which you don't want.

    # you did git init, added remote, added README file, add and commit then  pushed before making .gitignore
    # then you realized that you have unnessary file like README.md.swp
    # check what you have in the index
    $ git ls-files
    $ git rm README.md
    $ vim .gitignore # add contents in it and close
    # OR use .gitignore_global
    $ git config --global core.excludesfile ~/.gitignore_global
    $ git rm -r --cached .
    $ git add .
    $ git commit -m "fixed untracked files"
    
