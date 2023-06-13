# Git-Tricks

when adding nested folders to a repository you may encounter challenges when git files are created in the inner folder. To solve this,
you can delete the repo by delete@git-repo  /c/remove/repository (main-branch)
$ rm -fr .git

then add the files. Incase it is still problematic do : git rm --cached <foldername> , then
git add <foldername>
git commit -m "commit msg"
git push origin master
