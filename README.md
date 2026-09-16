# 🧪 Git Lab & Survival Guide

Welcome to my Git and GitHub laboratory! This repository was created as a testing
environment to master everything from basic commands to surgical operations in the
Git history. 

It now serves as my personal **Quick Reference Guide** (Cheat Sheet).

---

## ⚙️ Initial Setup (First Day on the Job)

Essential commands to run on a new computer before starting to code:

*   **`git config --global user.name "Your Name"`**: Sets the author name that
will appear in the version history for the team.
*   **`git config --global user.email "your.email@company.com"`**: Sets the email
address associated with your commits.
*   **`git config --global init.defaultBranch main`**: Forces Git to use `main` as
the default branch for new repositories (abandoning the old `master` default).
*   **`git config --global color.ui auto`**: Enables automatic terminal coloring
for easier reading.

---

## 🛠️ Essential Commands (Day-to-Day)

These are the core commands that solve 90% of daily needs:

*   **`git init`**: Creates a hidden `.git` folder, transforming the directory into
a trackable repository.
*   **`git clone`**: Clones a GitHub repository directly to the local machine.
*   **`git status`**: Shows the current state of files relative to `.git` and the
cloud.
*   **`git add .`**: Prepares all modified files for the next commit.
*   **`git commit -m "message"`**: Saves a safe "version" snapshot of your work state,
allowing you to revert if necessary.
*   **`git push`**: Sends local commits to the remote GitHub repository.
*   **`git pull`**: Pulls the latest changes from GitHub directly to the local
repository.

---

## 🚀 Advanced Tools (Rescue & Surgery)

When the basics aren't enough, these are the tools to save the day:

*   **`git stash`**: *The Interruption.* A temporary hidden drawer. It shelves
uncommitted changes so you can switch branches to handle emergencies, allowing you
to reapply the messy code later.
*   **`git reflog`**: *The Resurrection.* Git's secret diary. It allows you to see
where `HEAD` has been and recover accidentally deleted commits or branches.
*   **`git cherry-pick`**: *The Surgeon.* Allows you to pick a single specific commit
from one branch (e.g., a brilliant utility function amidst chaos) and copy it
precisely to your current branch.
*   **`git bisect`**: *The Detective.* A debugging tool that uses a binary search
algorithm to find in seconds exactly which commit introduced a fatal bug into the
system.
*   **`git rebase -i`**: *The History Rewriter.* Opens an interactive editor to squash,
delete, or rename older messy commits before pushing them to the cloud, maintaining a
clean history.

---

## ⚡ My Global Shortcuts (Aliases)

To speed up my workflow, I configured these global shortcuts in my terminal:
* `git a` ➔ `git add .`
* `git c` ➔ `git commit -m`
* `git s` ➔ `git status`
* `git co` ➔ `git switch`

*(To see how to revert or configure new shortcuts, visit this repository's [Wiki](https://github.com/laisvfm/git-lab/wiki/Git%E2%80%90Survival%E2%80%90Guide)).*
