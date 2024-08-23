# Git Commands Hub

This repository serves as a resource containing essential Git commands for quick reference.

## Getting Started

Before using Git commands, make sure you have Git installed on your system. You can download it from [Git's official website](https://git-scm.com/).

### 1. Configuring Git

Set your username and email address for Git commits:

```bash
git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"
```
View the current configuration:

```bash
git config --list
```

### 2. Initializing a Repository

To create a new Git repository, navigate to your project directory and run:

```bash
git init
```

### 3. Cloning a Repository

Clone an existing repository from a remote server (e.g., GitHub):

```bash
git clone <repository-url>
```

### 4. Checking Repository Status
View the status of your files in the repository (modified, staged, untracked):

```bash
git status
```

### 5. Adding Changes

Stage changes for the next commit:

```bash
git add <file-name>
```

To stage all changes, use:

```bash
git add .
```

### 6. Committing Changes

Commit your staged changes with a message:

```bash
git commit -m "Your commit message"
```

### 7. Viewing Commit History

To see the history of commits:

```bash
git log
```

### 8. Pushing Changes

Push your committed changes to a remote repository (e.g., GitHub):

```bash
git push origin main
```

Replace main with your branch name if different.

### 9. Pulling Changes

Fetch and merge changes from a remote repository:

```bash
git pull origin main
```

### 10. Branching

Create a new branch:

```bash
git branch <branch-name>
```

Switch to a different branch:

```bash
git checkout <branch-name>
```

Create and switch to a new branch simultaneously:

```bash
git checkout -b <branch-name>
```

### 11. Merging Branches

Merge a branch into the current branch:

```bash
git merge <branch-name>
```

### 12. Stashing Changes

Temporarily save changes that are not ready to be committed:

```bash
git stash
```

To apply stashed changes:

```bash
git stash apply
```

### 13. Viewing Remote Repositories

List the remote repositories configured for your local repo:

```bash
git remote -v
```

### 14. Removing Files

To remove a file from your repository and stage the removal:

```bash
git rm <file-name>
```

### 15. Resetting Changes

Unstage changes (move them from staged to unstaged):

```bash
git reset <file-name>
```

To reset your entire working directory:

```bash
git reset --hard
```

### Conclusion

These are some of the essential Git commands that you will use frequently. Understanding and mastering these commands will help you manage your codebase more efficiently.
