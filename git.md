# Good practices

##### Naming a commit
Depends mainly from company to company. Some companies likes to commit in present sentences, another ones in past sentences.

# Commands


| Task                            | Git command  |
| ------------------------------- | ------------ |
| initialize a repository         | `git init`   |
| add changes to the staging area | `git add`    |
| commit the changes              | `git commit` |
| status of the repository        | `git status` |
| read the commit history         | `git log`    |
| push changes to remote repo     | `git push`   |
| pull commits from remote repo   | `git pull`   |


Just type `git` in the terminal to get the main commands.

# Config

To know which user I am using. This name is only to show people who did the changes. Not necessarily the user of github.

`git config user.name`

Same for email

`git config user.email`

# Branching

less details
git log --oneline

to go to a specific commit
git checkout <commit id>

gitk 
basic visualization of branches


to know in which branch are we at
git branch 

to switch to another branch
git switch name-of-the-branch
git checkout name-of-the-branch

to create a branch from where we are
git checkout -b <branchname>

tto create a branch
git checkout -b <branch name> [start point]

renaming branches
git branch -m new-name

| Task                              | Command                         | 
| --------------------------------- | ------------------------------- | 
| go to a specific commit           | git checkout *commit-id*        | 
| to know in which branch are we at | git branch                      |   
| to create a new branch            | git checkout -b                 |     
| to switch to another branch       | git switch *name-of-the-branch* |     
| to rename a branch                | git branch -m *new-name*        |     


# Fork


