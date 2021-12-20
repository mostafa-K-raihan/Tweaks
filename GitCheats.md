**Delete multiple branch**

``
git branch -D `git branch | grep -E '{regex}'`
``

Here `-D` will permenantly delete your branch. 

`
``
` 
is important, and `-E`
will receive a regex pattern
