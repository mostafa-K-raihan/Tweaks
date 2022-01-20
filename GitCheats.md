**Delete multiple branch**
--------------------------
``
git branch -D `git branch | grep -E '{regex}'`
``

Here `-D` will permenantly delete your branch. 

`
``
` 
is important, and `-E`
will receive a regex pattern




**Hard Reset to latest remote master**
--------------------------------------
``
git reset --hard <remote-name>/master
``



**Use Local Branch Name as Remote while Pushing for the first time**
--------------------------------------
``
git push -u <origin> HEAD
``
