LOCAL GIT COMMANDS:
- **git status** : allows the user to look into the different files of its folder to see **whether they are committed or not**, to check their stages
- **git init** : **init folder .git** to the current folder
- **git add +file_name** : add a file to a **pre-commit state**. We can add all of the files using git add .
- **git commit -m** **commit the file with a message ** => %%this message gotta be in present%%!
- git log : see recent commits
-

- git clone + url allows to clone remote repo to local repo.

- checkout <branch_name> : allows to switch to an existing branch
- **create a branch** :
	- git checkout -b <branch_name> : **to automatically switch to the created branch
	- git branch <branch_name> : to just create one
- merge a branch to the main one : git merge <name_of_branch> (next it opens a vim editor to type a message, :q! ignore it )
- Push your current repo into the remote one : **git push -u "repo name (origin is the conventional)" (branch name : main)**
- **To check the current branch** : git branch
- Undo the added files : git rm --cached -r (name of the files, or . for all)
- Gitignore :
	- touch .gitignore : create the main file
	- Allows to hide to the public the files we've added into the .gitignore (1file to ignore per line)
		- It won't add the files when we do want to do this command : git add .
	- # to comment
	- *.txt = all the files with the text extension
- ![[screenshot-www.udemy.com-2023.08.05-15_04_20 1.png]]
- We can fork repo (copying an existing repository to make personalised changes) and after that we can make a pull request (propose to the creator to implement your changements into the official code) to the creator, which can be accepted or declined in the pull request section. 
	- When you do a fork, the creator is also the owner of the forked-repo
	- In its account he can see a new branch with ur username and see the changements