Trying to learn git and thier commands 
----------------------------------------------------------------------------------------------------------
To add the folder in git use cmd :-

 1)git --version

 2)git config --global user.name '----'

 3)git config --global user.email '----'

----------------------------------------------------------------------------------------------------------

To start git in terminal use cmd:-

 1) git init
 2) git status --> to check the status of all the files 
 3) git add filename (or git add . --> this cmd  will track all the uncommited files and add them all in just one click ) 
 4) git commit -m "write your commit message"

 ---------------------------------------------------------------------------------------------------------

 To change the name master with main use cmd :-
  1) git  branch -M main


----------------------------------------------------------------------------------------------------------
To add the origin to the remote file in git use cmd :-
 1) git remote add origin (paste the repo link here )

 2) git push -u origin main (all your files are added to git repo)

----------------------------------------------------------------------------------------------------------
To make branch and merge use cmds :-
 1) git branch branch-name --> this will create a new branch with diffrenet name

 2) git checkout branch-name --> to go to the newly created brnach 

 3) git checkout -b newBranch-name  ---> by this u can make new branch and also moveto that branch .(Shortcut)

 4) git branch new-branch-name souce-branch --> this will ensure that the new branch is created inside the right source branch  