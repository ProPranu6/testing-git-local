#Key points of the github tutorial

Git is a local representation or version control of the projects
Github is a global representation or version control of the projects

Git and Github have different tree representations which can be connected and updated from local git for following cases :

* Any new branches from Git when used through "push" command get updated on Github
* Any new branches on Github when used through "pull" command get updated on Git

#Note
* If any deleted branches exist on Github and the branches are not deleted on the Git then a pull request is not gonna delete the branches in Git to equate itself to Github
* Similarly any deleted branches on the git when pushed dont delete the branches on Github
* However the behaviour deleted files inplace of branches is not the same

#Key Steps to Setting up a Repository(which is just any folder of file or collection of foleders and files that is under the control of version control)

* Use CLI and initialise git with *git init* in the folder containing the project code
* Better create a branch with *git checkout -b <branch_name>* in the CLI
* Use *git add <filename>* to add all the files that have modifications and is ready to be commited, it is said to be in staged state
* Use *git commit* to commit all the changes to the branch that you are currently on
* To remotely connect to the github use the command *git add remote origin and <HTTPS_link> that's present on the repositry which is already created on the github
* Then use *git branch -M <name_of_main_branch>*
* Then use *git push -u origin <name_of_the_main_branch>* or *git push -all*, this pushes all of the data on the current working local branch to the main branch on github
* For any creations of new branches use *git checkout -b <branch_name>* by standing in the stream from where the new branch is to be created
* For any deletions of new branches locally use *git branch -D <branch_name>*
* For any deletion of branches on github use *git push origin -d <branch_name>
* For any pulls of data from github to git use *git pull --all* to pull all the updated data onto the branch that the local git is currently in
* Use *git branch <-r> or <-a>* to display the branches on remote or both remote and local
* Use *git status* to get the status of all the files in repo or on the branch 


