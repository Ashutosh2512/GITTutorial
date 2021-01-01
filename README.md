# GITTutorial

Below are some of the basic opeartions that we perform while using git. They are as follows:

Clone-  download a repository that is hosted somewhere on a remote repository.
Add-    track your files and canes made.
Commit- update your it with the changes made.
Push-   update git commits to a remote repo like Github.
Pull-   download changes made on your remote repo on your local machine.
Pull Request- It is created by a developer who has created a new branch and added some changes into the project to merge that branch with the main or master branch. So, why don't we directly work on master branch? The reason behind it is that the we only add well tested features of our product into the master branch so that it doesn't mess with the other features that have already been developed and our product doesn't malfunction.
Merge- When a pull request is created by a developer, then the owner of the repo must merge and resolve that pull request in order for the changes to be reflected into the main branch or another branch. 
Checkout- checkout means moving to another git branch. This may throw error if the changes made in a branch is not yet committed or stashed.
Merge Conflict- When we try and merge our current branch with master or another branch then it may throw an error because of the incompatible changes. 
Fork- We need to fork a repo, in order to create a new repo so that we will have full access to the copied repo and can then do the development and then create a pull  request to 
original repo.
Basic git commands:
git branch- lists all the branches present.
git branch -d <BRANCH_NAME>- delete  branch.
git reset <FILE_NAME>- It is used to unstage a file.
git reset HEAD~<Number_of_Commits_to_go_back>- It is used to uncommit the commits.
git log- gives a history of all the commits made
