# Git Branch Commands

A categorized list of essential Git commands related to branch management, both local and remote.

## **Branch Management**

| **Command**                          | **Description**                                                                 |
|--------------------------------------|---------------------------------------------------------------------------------|
| `git branch`                         | List all local branches.                                                        |
| `git branch -a`                      | List all branches (local and remote).                                           |
| `git branch -r`                      | List only remote branches.                                                      |
| `git branch <branch-name>`           | Create a new local branch.                                                      |
| `git branch -d <branch-name>`        | Delete a local branch (only if fully merged).                                    |
| `git branch -D <branch-name>`        | Force delete a local branch (even if it’s not merged).                           |
| `git branch -m <old-branch> <new-branch>` | Rename a local branch.                                                          |

---

## **Switching and Navigation**

| **Command**                          | **Description**                                                                 |
|--------------------------------------|---------------------------------------------------------------------------------|
| `git checkout <branch-name>`         | Switch to the specified local branch.                                           |
| `git checkout -b <branch-name>`      | Create a new branch and switch to it in one command.                             |

---

## **Integration and Updates**

| **Command**                          | **Description**                                                                 |
|--------------------------------------|---------------------------------------------------------------------------------|
| `git merge <branch-name>`            | Merge the specified branch into the current branch.                              |
| `git rebase <branch-name>`           | Rebase the current branch onto the specified branch.                             |
| `git pull`                           | Fetch updates from the remote repository and merge them into the current branch. |
| `git pull origin <branch-name>`      | Fetch and merge a specific remote branch into the current branch.                |
| `git cherry-pick <commit-hash>`      | Apply a commit from one branch to the current branch.                            |

---

## **Remote Branch Operations**

| **Command**                          | **Description**                                                                 |
|--------------------------------------|---------------------------------------------------------------------------------|
| `git push origin <branch-name>`      | Push a local branch to the remote repository.                                    |
| `git push origin --delete <branch-name>` | Delete a remote branch.                                                         |
| `git push`                           | Push local changes to the remote repository for the current branch.             |
| `git push -u origin <branch-name>`   | Push a branch and set up a tracking branch with the remote repository.           |

---

## **Fetching Updates**

| **Command**                          | **Description**                                                                 |
|--------------------------------------|---------------------------------------------------------------------------------|
| `git fetch`                          | Fetch updates from the remote repository without modifying the working directory. |
| `git fetch --all`                    | Fetch updates for all remote branches.                                           |
| `git remote show origin`             | Show details of the remote repository, including branches.                       |

---

## **History and Logs**

| **Command**                          | **Description**                                                                 |
|--------------------------------------|---------------------------------------------------------------------------------|
| `git log <branch-name>`              | Show the commit history of a specific branch.                                    |
| `git log --oneline --graph --decorate` | Show a compact commit history with a graphical representation of branches.       |
