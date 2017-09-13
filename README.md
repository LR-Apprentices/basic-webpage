# Apprentice-Website

## To run Flask

```
pip install -r requirements.txt
python run.py
```

Then navigate to 'localhost:5000'

[Anna's commands](#anna)

[Luke's commands](#luke)

[Jess' commands](#jess)

[Alex's commands](#alex)

[The Static Site](#static-site)

## Anna
## Github commands

### How to git push and commit
```
	1.	Firstly, when I am in the correct folder, I type git status.
	2.	git status
	3.	This shows the red files which are not commited, and the green files which are.
	4.	git add .
	5.	This adds all the files to the commit
	6.	git commit -m "Your message "
	7.	This adds a little message to the commit
	8.	git push
	9.	This pushes the files up to the branch.
```

## Useful link for learning Git

https://www.atlassian.com/git/tutorials/learn-git-with-bitbucket-cloud/git-branch-to-merge

-----------------------------------------------------------------------------------------------------------------------------

## Luke
## Git-Help

How to link a folder to github (make sure git/git bash is installed)

To start we will make a seperate folder (name of your choice) once done open git bash by rightclicking in the folder you just made and click the Git Bash here and write the following codes

```
$ git init
```

this creates a local repo

or type

```
$ git clone https://github.com/LR-Apprentices/Apprentice-Website.git
```

this will clone a repository from github's master branch to your local folder

now we want to make a branch
to do this we will type

```
$ git checkout -b 'insert name'
```

so now the folder will represent that branch

we will now want to learn how to commit the branch and push it to the website so it knows about the branch
to do this type

```
$ git status
```

this shows you all the changes made
to add them to the commit type

```
$ git add .
```
alternatively you can add a single file by typing
```
$ git add filename.txt
```

now we will check the status again to see if the modified files show in green (this means they are added)

```
$ git status
```
this is so that we know if it has it added
now to commit it
type

```
$ git commit -m "Enter a message that represents the changes"
```

now we want to push the file and branch to the website to do this type
```
$ git push --set-upstream origin nameofbranch
```

after the branch is made you will only need use the code below to add files to the branch
```
$ git push
```
now it should have pushed to the website including your new branch


-----------------------------------------------------------------------------------------------------------------------------


## Jess
## Git-Help

This is a website project created by the apprentices who joined Land Registry in October 2016, ready for next years apprentices.
This document will give the people working on this project.

 # Git Commands

     $ git status
 Viewing the changed files in your working directory.

     $ git diff

 Viewing tracked file changes

     $ git add .

 Add all current changes to the next commit.

     $ git add -p <file:>

 Add some changes that was created in the files to the next commit.

     $ git commit -a:

 Commit all local changes in tracked files.

     $ git commit -m "changed action"

 This command commits everything which is in staging area to the local repo. -m means you are sending a commit message, so other people can see what was changed since last commit.

 # Commit History

     $ git log

 This command shows all the latest commits. Started from the newest commit that was made.

     $ git log -p <file>

 If you wanted to see changes that were made to one file over time, you can do that by using the command above.

 # Branches
     $ git branch -av

 This command list all the existing branches in the repository

     $ git checkout <branch-name>

 This command points the branch that you want to work on, in your working directory (HEAD Branch)

     $ git branch <new-branch>  

 This command creates a new branch in the repository.

     $ git checkout --track <remote/branch>

 This command creates a new tracking branch based on a remote branch.

     $ git branch -d <branch>

 This command deletes a branch locally.

 # Update and Publish
     $ git remote -v
 This command shows all the configured remotes linked to your local repository. Eg github. This is an example:

     $ git remote -v
     origin  https://github.com/LR-Apprentices/Apprentice-Website.git (fetch)
     origin  https://github.com/LR-Apprentices/Apprentice-Website.git (push)

     $ git remote origin

 Shows information about the remote repositorys stored online. Here is an example of the output of our repo.

         * remote origin
         Fetch URL: https://github.com/LR-Apprentices/Apprentice-Website.git
         Push  URL: https://github.com/LR-Apprentices/Apprentice-Website.git
          HEAD branch: master
          Remote branches:
     Alex                                 tracked
     Annas-branch                         tracked
     Jess                                 tracked
     Lukes-Branch                         tracked
     master                               tracked
     refs/remotes/origin/ALuffy87-patch-1 stale (use 'git remote prune' to remove)
     Local branches configured for 'git pull':
     Jess         merges with remote Jess
     Lukes-Branch merges with remote Lukes-Branch
     master       merges with remote master
      Local refs configured for 'git push':
     Jess         pushes to Jess         (up to date)
     Lukes-Branch pushes to Lukes-Branch (up to date)
     master       pushes to master       (up to date)

 Hopefully that should give you more of an idea.

     $ git remote add <shortname> <url>

 Adds new remote repository. For example, if you had the same stuff saved on gitlab, you can add it.

     $ git push

 Pushes all of the commits from the staging area to the remote repo. In our case it is Github. Or you can just choose to push one file.

     $ git push --set-upstream origin branch_name

 Pushes the newly created branch to github. Alternatively, you could create a new branch on Github.

     $ git pull

 Downloads the changes that is done from all branches and commits from other machines onto your working directory.

     $ git fetch

 Fetches all the changes from all of the remote repos, but it doesn't affect the branch you are currently on.

     $ git branch -dr <remote/branch>

 This command deletes the branch off GitHub.

 -----------------------------------

## Alex

```
$ git checkout
```
I've learnt the process of git checkout as it transfers the folder from one branch to another.
```
$ git pull
```
Completes the transfer of files between all the branches from the repository.
```
$ git push
```
Commits the files that have been worked on back to the repository.
```
$ git commit -m "Text that represents the change"
```
Commits it to your local repository, which puts it in a status ready to push.

------------------------------------

# Static Site


Currently this is the quick setup of the static site, if we need other things added, I will add them, as for now this is the baseline that I have made for it

--------------------------------

## To use it

To use this is simple enough, so long as all 3 files are in the same area it will work. Open the Homepage.html and there are links at the top to both homepage and the alternate page, this is all linked to the css file aswell so it should have a grey background-color with some simple text in the middle of the page
