git -> version control
used to track the changes made inside a file
helps to work collabaratively on a project



some commands

git log -> shows all the history of the commit

git log --oneline -> shows the summmary of the commit

git show <commit hash> -> shows the detail of a specific commit(we can get the hash of a commit by git log)

--------------------------------------------------------------------------------------------------------------


Git Branch  -> In Git, a branch is like a separate workspace where you can make changes and try new ideas without affecting the main project
using it we can work on different on features and bugs withour affecting the main branch and after commit we can  merge out feature with the main

command->
git branch otp-genration  -> this is the branch i have created to work on generating otp ,  after successfull doing it i will merege it with my main or master branch.
To see this branch on the github we have to run this command -> git push -u origin branchname

SWITCHING BETWEEN BRANCHES 

git checkout otp-generation
-> by doiing it we are switiching to otp generator branch to work in it , we have swithced our workspace from master/main to otp-generator 


now after doing work in this new branch we can push it as -->   ( git push -u origin new_branch_name)

now on github we have to compare the chnages and we have to (CREATE PULL REQUEST) so as to merge this chnage withthe main/master branch.

Merging in Git means combining the changes from one branch into another. 

# HOW TO MERGE CHANGES FROM new_branch TO MAIN/MASTER using git command

# step 1 :  swith to the branch we merge into like here we have to merge into master so first switch to master using git checkout.
# step 2 : then use command -> git merge otp-generator
# step 3 : now push it in master as -> git push -u origin master


<!-- 

The Three Areas of Git
Working Directory: Where you make changes to your files.
Staging Area (Index): Where you prepare changes before committing.
Repository: Where your co-->

[Working Directory] --git add--> [Staging Area] --git commit--> [Repository]
   

