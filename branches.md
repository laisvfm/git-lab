# Git Branches — Quick Reference

## Create and switch
git switch -c feature/name

## Switch branches
git switch main
git switch feature/name

## List branches
git branch
git branch -a
git branch -r

## Merge
git switch main
git merge feature/name

## Delete local branch
git branch -d feature/name

## Push a new branch
git push -u origin feature/name

## Update remote references
git fetch
git fetch --prune

## Abort a merge
git merge --abort
