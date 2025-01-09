# Git Commands Reference

| **Category** | **Command** | **Description** |
| --- | --- | --- |
| **Git Configuration** | `git config --global user.name \"Name\"` | Set your global username. |
|  | `git config --global user.email \"email@example.com\"` | Set your global email. |
|  | `git config --global color.ui auto` | Enable colored output in the terminal. |
|  | `git help` | Display Git help documentation. |
| **Repository Initialization** | `git init` | Initialize a new Git repository. |
|  | `git init <directory>` | Initialize a Git repository in a specified directory. |
|  | `git clone <repository_url>` | Clone a repository from a remote to your local machine. |
|  | `git clone --branch <branch_name> <repository_url>` | Clone a specific branch from a repository. |
| **Staging and Changes** | `git add <file>` | Stage a specific file. |
|  | `git add .` or `git add --all` | Stage all modified and new files. |
|  | `git status` | Show the repository's status, including untracked and staged files. |
|  | `git status --ignored` | Include ignored files in the status output. |
|  | `git diff` | Show unstaged changes between working directory and staging area. |
|  | `git diff --staged` or `git diff --cached` | Show staged changes relative to the last commit. |
|  | `git diff <commit1> <commit2>` | Compare differences between two commits. |
| **Committing Changes** | `git commit -m \"<message>\"` | Commit staged changes with a message. |
|  | `git commit -a -m \"<message>\"` | Commit all tracked file changes directly, bypassing staging. |
|  | `git commit -m \"feat: message\"` | Commit indicating a new feature. |
|  | `git commit -m \"fix: message\"` | Commit indicating a bug fix. |
|  | `git commit -m \"docs: message\"` | Commit documentation changes. |
| **Branching and Merging** | `git branch` | List all local branches. |
|  | `git branch <branch-name>` | Create a new branch. |
|  | `git branch -d <branch-name>` | Delete a local branch. |
|  | `git branch -a` | List all local and remote branches. |
|  | `git checkout <branch-name>` | Switch to a branch. |
|  | `git checkout -b <branch-name>` | Create and switch to a new branch. |
|  | `git merge <branch>` | Merge the specified branch into the current branch. |
|  | `git stash` | Save changes in a stash to work on another task without committing. |
|  | `git stash pop` | Apply and remove the most recent stash. |
| **Remote Operations** | `git fetch` | Fetch changes from the remote repository without merging. |
|  | `git fetch --prune` | Remove stale references to remote-tracking branches. |
|  | `git pull` | Fetch and merge changes from the remote repository. |
|  | `git pull --rebase` | Fetch changes and rebase your branch on top of the updated branch. |
|  | `git push` | Push local commits to the remote repository. |
|  | `git push --all` | Push all branches to the remote repository. |
|  | `git remote` | List all configured remote repositories. |
|  | `git remote add <name> <url>` | Add a new remote repository. |
| **History and Comparison** | `git log` | Show commit history for the current branch. |
|  | `git log --all` | Show commit history across all branches. |
|  | `git show <commit>` | Show details of a specific commit, including changes. |
|  | `git diff HEAD` | Show changes in the working directory relative to the last commit. |
|  | `git revert <commit>` | Create a new commit that reverses changes introduced by a specific commit. |
| **Tagging** | `git tag` | List all tags in the repository. |
|  | `git tag <tag-name>` | Create a lightweight tag at the current commit. |
|  | `git tag -a <tag-name> -m \"<message>\"` | Create an annotated tag with a custom message. |

