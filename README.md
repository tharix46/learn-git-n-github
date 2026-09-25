# Welcome to Git & GitHub!

This repo is created to learn **Git and GitHub** - starting with Git basics, then moving on to GitHub.

---

### ⚠️ IMPORTANT!

This repo **DOES NOT** contain any **CODE**. Its sole purpose is to **get hands dirty with version controlling**.

---

### Git

Git is a distributed version control system. It is used to track changes in source code including who made changes.

---

### GitHub

GitHub is an online cloud-based platform that allows us to store our git repositories and collaborate with others.

---

### Git Version & Help

```bash
git --version

git help
git help <command>
git help --all
```

---

### Git Config

Let Git know who you are. Git uses this information to identify who made commits.

```bash
git config --global user.name "<your name>"
git config --global user.email "<your email>"

# view git config
git config user.name
git config user.email
git config --list
```

---

### Git Basic Commands

```bash
# initialize a new git repo
git init

# view status of the repo
git status

# create and switch to a new branch
git checkout -b <branchName>

# add files to the staging area
git add <file>
git add .

# commit staged files
git commit -m "<commit message>"

# view git commit log
git log --all --graph
```

---

### Work With Remote

```bash
# link a remote repo
git remote add origin <url of the repo>

# push local branch to remote
git push -u origin <local branch name>

# pull changes from remote to local
git pull origin <remote branch name>

```

---

### Git Reset

Moves HEAD back and clears the Staging Area to match that commit.

```bash
git reset <commit hash>
```

---

### Git Revert

Creates a new commit that undoes the changes of a previous commit.

```bash
git revert <commit hash>
```

---

### Git Stash

```bash
git stash
git stash list
git stash apply <stash name>
```

---
