-> The history of the total project will be saved in the git repository.
-> The untracked files are the files which are not yet committed i.e. the history of the files are didn't save in the project.
-> After creating a new repository in github we can get the new repository url,we need to add that repository to our project,for that the command will be "git remote add origin url ",
here the git is git ,remote means we are going to work with urls, and add means adding the url
and origin means that the url we are going to add, url means url
-> After connectig with the repository we need to push the changes that have been made in the project to see the changes in the repository
-> All the commits that are been made, will be done in the main branch but ,that code is not finalised coz there are several members that had been doing committs in the main branch, so that we will create a new branch to do our commits.
-> we cannot make any changes to anyone's account directly without their permission ,but we can make a copy of the project by forking it . if we have approval to that project then we can make changes directly
-> if you want to merge your code with the main project you need to create a pull request and if they agreed for your pull request you can merge with the main code.
-> And make clear that one branch = one pull request.
-> so if you want to add different versions of your code to the main branch you need to have different pull requests.so that u should create different branches for different things which is so recommended.
-> if we delete any commits by using reset method,the online repository contains the file, so u need to have force push it

Uses of github:-

1. maintaining and sharing the code all around the world
2. maintaining the history of the project that when its updated at what time and what date

commands:-

1. ls - list the no of folders
2. mkdir filename - make directory project
3. cd - change directory - to go inside thre project
4. git init - initiliaze a empty git repository i.e. a folder
5. ls -a -- to see all the hidden files
6. touch - to create a new file in the directory
7. git status - to see any modified or added i.e any changes is done and didn't save in the history of the project
8. git add filename- Adding a file to the staging area i.e. which are ready to commit
9. git add . - Adding all files to the staging area i.e. (.) represents all files
10. git commit - m "message" -- committing the file i.e. saving the history of the file with a message
11. cat filename - it basically displays wtever things are available in the file
12. git restore --stagged filename -- it removes the files from the staging area
13. git log - to see the history i.e. all the commits
14. git reset (id) - all commits are saved one by one ,if we want to delete some commits u need to copy the id and use this coomand with the id of the commit which u want to be in the log.
15. rm - rf filename -- to delete a file
16. git stash -After making changes if we dont want to commit and as well as we dont want to lose the changes ,we can send those changes to staging area with git stash.
17. git stash pop - and if we want toget back those changes we can use this command.
18. git stash clear - to delete all the things that are present in the staging area.
19. git push origin master - to push the changes to the folder i.e. repository that have been made in the project
20. git branch branchname - to create a new branch
21. git checkout branchname - to change the head to the specific branch
22. git merge branchname - to merge with the main branch or some specific branch
23. git push origin master - to push the commits to the master branch
24. git push origin branchname -f -- to force push the file
25. git rebase -i -- to merge commits in one commit by using squash with s command

what is head?
-> Head is just a pointer that says all the commits that we r going to made will be committed in that head points branch.
what are merge conflicts ?
-> if two people are making changes in the same line in the same code then the github will confuse whch change should i take and those conflicts will be resolved by the rigin master
