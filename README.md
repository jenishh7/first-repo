
# Git Workflow Guide

## Check Git Version
```bash
git --version
```

## Configure Git
Set your Git username and email globally:
```bash
git config --global user.name "your_username"
git config --global user.email "your_email@example.com"
```
To verify your configuration:
```bash
git config --global --list
```

## Clone a Repository to Your Local Machine
To clone a repository:
```bash
git clone <repository-url>
cd <repository-directory>
```

## Track Changes in Your Project
Check the status of your files:
```bash
git status
```

## Understanding File Status
Git categorizes your files into four states:
1. **Untracked**: New files that haven't been added to the repository.
2. **Modified**: Files that have been changed but not yet staged.
3. **Staged**: Files that are marked to be committed in the next snapshot.
4. **Unmodified**: Files that haven't changed since the last commit.

## Save Your Changes in Two Steps
1. **Add files to staging area**:
   ```bash
   git add <file-name>  # Add a specific file
   git add .            # Add all changes in the current directory
   ```
2. **Commit your changes**:
   ```bash
   git commit -m "Your commit message"
   ```

## Push Your Changes to the Remote Repository
Send your commits to the main branch:
```bash
git push origin main
```
