## Basic Commands

| Command                   | Description                                              |
|---------------------------|----------------------------------------------------------|
| `git init`                | Initialize a new Git repository in the current directory |
| `git clone <url>`         | Clone a repository from a remote location                |
| `git add <file>`          | Add a file or directory to the staging area              |
| `git commit -m "message"` | Commit changes to the repository with a message          |
| `git status`              | Show the status of the current repository                |
| `git log`                 | Show the commit history of the current branch            |

## Branches

| Command                | Description                                    |
|------------------------|------------------------------------------------|
| `git branch`           | List all branches in the current repository    |
| `git branch <name>`    | Create a new branch with the given name        |
| `git checkout <name>`  | Switch to the given branch                     |
| `git merge <name>`     | Merge the given branch into the current branch |
| `git branch -d <name>` | Delete the specified branch                    |

## Remote Repositories

| Command                       | Description                            |
|-------------------------------|----------------------------------------|
| `git remote add <name> <url>` | Add a new remote repository            |
| `git pull <remote> <branch>`  | Pull changes from a remote repository  |
| `git push <remote> <branch>`  | Push changes to a remote repository    |
| `git fetch <remote>`          | Fetch changes from a remote repository |

## Undoing Changes

| Command                  | Description                                                          |
|--------------------------|----------------------------------------------------------------------|
| `git checkout -- <file>` | Discard changes to a file in the working directory                   |
| `git reset HEAD <file>`  | Unstage changes to a file                                            |
| `git reset <commit>`     | Undo commits up to the specified commit                              |
| `git revert <commit>`    | Create a new commit that undoes changes made in the specified commit |

## Advanced Commands

| Command                    | Description                                                          |
|----------------------------|----------------------------------------------------------------------|
| `git stash`                | Stash changes in the working directory                               |
| `git cherry-pick <commit>` | Apply the changes made in the specified commit to the current branch |
| `git rebase <branch>`      | Reapply commits on top of another branch                             |
| `git submodule`            | Manage submodules within the repository                              |
