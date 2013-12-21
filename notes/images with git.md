# Images with git

    # make a directory and cd to it.
    $ mkdir ~/Github_wiki && cd $_
    # clone your wiki
    $ git clone git@github.com:USER/REPO.wiki.git
    # create a image dir and cd to it.
    $ mkdir images && cd -
    # add images in images dir
    $ mv ~/somedir/someimage.png ~/Github_wiki/REPO.wiki/images/someimage.png
    # add, commit and push it
    $ git add .
    $ git commit -m "someimage.png added"
    $ git push origin master

Go to your wiki and add a sample page and add the following.

    
    ![sample image](images/vimnote1.png)
    The above image is added with `![sample image](images/someimage.png)`
    This image can be found here, https://raw.github.com/wiki/shinokada/vimnotes/images/someimage.png

Adding link to an image.

    [![Alt attribute text Here](images/someimage.png)](http://google.com)

## Sample in README page


![sample image](https://raw.github.com/wiki/shinokada/vimnotes/images/vimnote1.png)


## Resources

[Stackoverflow](http://goo.gl/pWYDnR)
[my github page](https://github.com/shinokada/gitnotes/blob/master/notes/images%20with%20git.md)

