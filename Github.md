# Github Cheat Sheet

## Configuring user information

### Setup Git username
```
git config --global user.name "your username"
```

### Setup Git email
```
git config --global user.email "your email"
```

### To check the list detail
```
git config --list
```

### Create a new local repository
```
git init
```

### Clone a repository
```
git clone <repository-url>
```

### Add a file to the staging area in Git
```
git add [file]
```

### Add all files in the staging area in Git
```
git add .
```

### Check a repository's status in Git:
```
git status
```

### Commit changes with a message in Git
```
git commit -m "your commit message here"
```

### To Check the unstaged changes
```
git diff
```

### Add changes made to track files and commit
```
git commit -a -m "Your Message"
```

### Reset staging area from last commit
```
git reset <filename>
```

### Remove a file from the index and working directory
```
git rm <filename>
```

### List the commit history
```
git log
```

### To display branches
```
git branch
```

### To create a branch
```
git branch <branch name>
```

### To switch to a branch
```
git checkout <branch name>
```

### To delete a branch
```
git branch -d <branch name>
```

### To merge a branch
```
git merge <branch name>
```
### Sync your fork or your local repository with the origin repository
```
git fetch upstream
```

### Push your local commits to the remote repository
```
git push origin YourBranchName
```

### To pull changes from a remote repo in Git
```
git pull
```

### To get the contents of remote branches in Git without automatically merging
```
git remote update
```

### To push a new branch to a remote repo in Git
```
git push -u origin branch_name
```

### To force a push request in Git
```
git push -f
```

