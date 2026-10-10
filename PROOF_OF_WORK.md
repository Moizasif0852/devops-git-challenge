# Proof of Work — DevOps Git Challenge

## 1. Git Commit History

```bash
git log --oneline --all
```
└─$ # Proof of Work — DevOps Git Challenge                                                                                                  
git log --oneline --all
56d2a66 (HEAD -> main, origin/main) Merge pull request #1 from Moizasif0852/development
79e92e0 (origin/development, development) fix: resolved merge conflict
eaeaf77 (origin/staging, staging) fix: staging label
56c4d89 feat: updated script with staging env
f64e0f0 feat: initial commit with deploy script
                                                                                                                                            
┌──(kali㉿kali)-[~/devops-git-challenge]
└─$ 


## 2. Reflection Questions

### Q1: Difference between Git and GitHub

**Git** is a tool that tracks changes in files on my computer. **GitHub** is an online platform where I can store my Git repositories and share my work with others.

### Q2: Explain the Three Architecture Stages

- **Working Directory:** Where I create and edit files.
- **Staging Area:** Where I select changes for the next commit using `git add`.
- **Local Repository:** Where Git saves committed changes and their history.

### Q3: Difference between `git stash pop` and `git stash apply`

- **`git stash pop`:** Restores saved changes and normally removes them from the stash list.
- **`git stash apply`:** Restores saved changes but keeps them in the stash list.

### Q4: Difference between `git fetch` and `git pull`

- **`git fetch`:** Downloads updates from GitHub without merging them into my current branch.
- **`git pull`:** Downloads updates and integrates them into my current branch.
