## GITHUB GROUP ACTIVITY
For performing different operations on git using terminal we created a four members group.The menbers are Riya Jofi,Sana Earnest,Saniya Thahseen and Sariga M.S.We selected Saniya as our group leader.Therefore we take leader's repository as the master branch.The different operayions we performed are as follows:
#### *Step 1:Repository creation*
1.First we created a repository 'SDLab' on github.
2.Then created a group members file in that repository
3.The master invited us and we accept the invitations.
#### *Step 2:Cloning Git Repository*
For cloning the git repository to our local repository,we copy the git repository link from github.Then git lone command is as follows:
>git clone git@github.com:[sanaearnestse/SDLab.git]()
#### *Step 3:Git Initialization*
>git init

This command initialized an empty git repository **/home/mca56/sanrepo/project2/.git**
>cd SDLab

This command is used for change the directory.
#### *Step 4:Push Operation*
To perform push operation the following operations are needed.
1.Copy and paste a file in the remote repository.Here I paste **san.txt** file
2.Add the file using the below command
>git add san.txt

3.Git commit operation
>git commit -m "sana's first commit"

When we commit the files are added to the git repository.

4.Pull operation
>git pull

We perform pull operation before every push to understand the changes in the repository.The git pull operation shows alreay existing files.When we tried to  perform git push before pull operation,a message "git push rejected" was shown.
5.Push operation
>git push origin master

After this command we login to git from terminal and the files are added to remote repository.

#### *Step 5:Branch in git*
1.Creating a new branch
>git checkout -b sanabranch

If create branch then we can get the message "switched to a new branch"
2.Adding files to branch.
>git add greater.sh

>git commit -m "my first branch commit"

>git pull

>git push origin sanabranch

Since we were used git checkout command the merging opeation is automatically performed.

>git log --a
 
This command list out all the branches.

>git status

This commandand shows the current branch in the repository.

#### *Step 6:Git Rebase Operation*
>git rebase 149ffg88998cd58881

The rebase operation adds the base of the current branch to the given commit id .It changes the base to a new position.

>git log --graph
 
This command will shows a graph that contains all the activities we performed on git.This graph helped us to clearly understand the flow of all opeartions.
 
---
To prepare this mark down file I used **Document Node** tool.This tool is very easy to understand and we can easly format our document using this tool.To format the document 'format' tool is available in this tool.We can also run our file in this tool.




