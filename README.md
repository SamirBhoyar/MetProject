# DemoProject -Author - Samir Bhoyar
<br>
# Git command
------------------------------

-git clone "----http-link of github code"
-git status    //to check the status of repository.

//type of status:<br>
1> untracked : If you create new file in local and which is not present on remote <br>
2>Modified : File is present in both loca and remote, but yopu  resently made some changes and haven't add and commited yet.<br>
3>Staged : file is ready to be committed. You have add the file but yet to commit. it will show in Staged.<br>
4>unmodified : there is no change in local file and it is exact as remote file.<br>

-git add <-file name-><br>
-git commit -m "new update"  // record of change.<br>
-git push origin main/master //upload local repo content to remote repo.<br>

-git init // if you have create the new project in local, and now you want to add it to remote(github repo). you need git in local new project folder. for that we use git init command.<br>

-git remote add origin <-new repo link> // you this command to link new created repo on github, to new create project on local<br>

-git remote -v // to verify the remote<br>
-git branch   // to check branch<br>
-git branch -M newName // to rename brach<br>

-git push -u origin main // through this you can set upstream or branch. so that you dont need to right "git push origin main ",insted you can just righ "git push" simply to push. <br>
---------------------------
<br>


# branch Command
------------------

-git branch   // to check current branch<br>
-git branch -M newName // to rename brach<br>
-git checkout <-branch name>  // to navigate<br>
-git checkout -b <-new branch name-> //to create new branch<br>
-git branch -d <-branch name-> //to delete branch<br>


merge command:
--------------

-git diff <-other branch name> //to compare current branch commits,branches,file and more with other branch.<br>
-git merge <-branch name>  //to merge 2 branches<br>

-git pull origin  main   // used to fetch and download cotent from a remote repo and immediately update the local repo to match that content.<br>


# Undoing Changes
---------------

Case1: staged changes<br>

-git reset <-fileaname><br>
-git reset<br>

Case2: commited changes(for one commit)

-git reset HEAD-1   //remove last change<br> 

Case3 : commited changes (for many commits)
-git reset<-commit hash> // remove commit.<br>
-git reset --hard<-commit hash>  //to remove commit and code from repo folder.<br>

Resolving Merge confilcts: an event that takes place when Git is unable to automatically resolve difference in code between two commits.<br>


