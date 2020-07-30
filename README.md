# Practice repository to start learning Git
 ## Commands used

 - git init: Create repo
 - git status: Compare working directory, staging aread, and current branch
 - git commit
 - git config: Set or get configuration
 - git log: Show history of project commits
 - git branch -c: create branch
 - git checkout: switch branches
 - git merges: Merge changes from different branches
 - git remote add <remote> <url>: Add a new <remote> and <url>
 - git remote -v: List remote repos
 - git push -u <remote> <branch>: Push <branch> to <remote>, and set default upstream for <branch>
 - git branch: list branches
 - git checkout branchname: checks out a branch
 - git checkout -b branchane: creates branch then checks it out
 - git stash: Hide uncommitted changes before switching branches
 - git stash pop: Brings last item stashed back into the working directory
 - git stash list: List all stashes in branch

 - git diff: show the difference between commits, the working directory, and the staging area
 - git diff <commit>: Show diff between staged changes and that particular commit
 - git diff --cached: diff between staging area and head
 - git diff <commitA>..<commitB>: diff between two commits
 - git diff <branchA>..<branchB>: diff between branches


 - git log --author <string>: show all commit with matching author
 - git log --since <date>: show commits since date
 - git log --until <date>: show commits prior to last date
 - git log --oneline: only show a single line summary
 - git log --graph: show graph view of commits
 - git log --all: shows all commits across branches

 ## Commit messages
 Default editor is vim

## Merging
Merging means to bring the changes from one branch into another.

- A fast forward merge happens when the target branch was branched from the current one, and there are no new changes to the current branch since then.

blah blah blah
