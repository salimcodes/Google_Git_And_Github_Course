Introduction to Git and GitHub by Google

![image](https://user-images.githubusercontent.com/64667212/141744791-d079bf2b-f3cd-4e45-8c86-18d36ebe20a0.png)

About this Course

In this course, you’ll learn how to keep track of the different versions of your code and configuration files using a popular version control system (VCS) called Git. We'll also go through how to setup an account with a service called GitHub so that you can create your very own remote repositories to store your code and configuration. 

![image](https://user-images.githubusercontent.com/64667212/141744961-62520c90-936b-41a2-aa82-4b5c51cef2af.png)

Throughout this course, you'll learn about Git's core functionality so you can understand how and why it’s used in organizations. We’ll look into both basic and more advanced features, like branches and merging. We'll demonstrate how having a working knowledge of a VCS like Git can be a lifesaver in emergency situations or when debugging. And then we'll explore how to use a VCS to work with others through remote repositories, like the ones provided by GitHub.

By the end of this course, you'll be able to store your code's history in Git and collaborate with others in GitHub, where you’ll also start creating your own portfolio! 

In order to follow along and complete the assessments, you’ll need a computer where you can install Git or ask your administrator to install it for you.


# Also, here is a Git Cheat Sheet 
===========================================================

> I hope this helps! 

## Configuring you Git 

| Syntax | Description |                        
| :--- | :--- |                                                                                
| $ git config --global user.name "Username" | Sets the name you want attached to your commit transactions |          
| $ git config --global user.email "Email" | Sets the email you want attached to your commit transactions |             
| $ git config --global color.ui auto | Colorization of command line output |                                 

	
 ## Creating Repository

| Syntax | Description |                        
| :--- | :--- |                                                                                
| $ git init | Turn an existing directory into a git repository |          
| $ git clone [url] | Clone a repository that already exists on GitHub |             


 ## Operations on Files

| Syntax | Description |                        
| :--- | :--- |                                                                                
| $ git add <filename> | Adds a file to Staging area |          
| $ git add * | Adds all files to Staging area | 
| $ git commit -a | Stages files automatically |
| $ git log -p | Produces patch text |
| $ git show | Shows various objects |
| $ git diff | Can show the differences in various commits |
| $ git diff --staged | Show all staged files compared to the named commit |
| $ git add -p | Allows a user to interactively review patches to add to the current commit |
| $ git mv | Moves a file |
| $ git rm | Removes a file |
	

## Reverting Changes 

| Syntax | Description |                        
| :--- | :--- |                                                                                
| $ git reset | Resets the repo, throwing away some changes |          
| $ git commit --amend |  Make changes to commits |             
| $ git revert  | New commit which effectively rolls back a previous commit |


 ## Branches

| Syntax | Description |                        
| :--- | :--- |                                                                                
| $ git branch | Used to manage branches |          
| $ git branch <name> | Creates the branch | 
| $ git branch -d <name> | Deletes the branch |
| $ git branch -D <name> | Forcibly deletes the branch |
| $ git checkout <branch> | Switches to a branch |
| $ git checkout -b <branch> | Creates a new branch and switches to it |
| $ git merge <branch> | Merge joins branches together |
| $ git merge --abort | abort the merge action (In case of merge conflict) |
| $ git log --graph --oneline | This shows a summarized view of the commit history for a repo |
	

## Interaction with Remote Repository

| Syntax | Description |                        
| :--- | :--- |                                                                                
| $ git push | Git push is used to push commits from your local repo to a remote repo |          
| $ git pull | Git pull is used to fetch the newest updates from a remote repository |  


 ## Remotes

| Syntax | Description |                        
| :--- | :--- |                                                                                
| $ git remote | Lists remote repos |          
| $ git remote -v | List remote repos verbosely | 
| $ git remote show <name> | Describes a single remote repo |
| $ git remote update | Fetches the most up-to-date objects |
| $ git fetch | Downloads specific objects |
| $ git branch -r | Lists remote branches; can be combined with other branch arguments to manage remote branches |
	
	 	
	
	
	
	
	
