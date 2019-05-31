# Git

## Pushing code to new repository

  `git push -u origin master`

## Cloning the repository

  `git clone https://github.com/{username}/{repository name}.git`

## Basic git commands

  `git status`

  `git add {filename}` or `git add .`

  `git commit` or `git commit -m "{msg}"`

## Pushing new branch

  `git push -u origin {branch name}`
  
## Updating forked repository

  ```
  git remote add upstream https://github.com/{owner}/{repository}.git
  git fetch upstream
  git checkout master
  git rebase upstream/master
  git push -f origin master
  ```
  
## Squashing Commits

  `git rebase -i HEAD~N` (N = no. of commits you want to squash)
  
  then choose 'pick' or 'squash' from the text editor
