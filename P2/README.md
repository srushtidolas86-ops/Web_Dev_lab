# P2 – Portfolio repo with an initial commit

## Aim
Create a Git repository for the portfolio and save its first version.

## Commands
Run these inside the project folder:
```bash
git init
git status
git add .
git commit -m "Initial portfolio setup"
```

To connect an existing GitHub repository:
```bash
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/YOUR-REPOSITORY.git
git push -u origin main
```

If a remote named `origin` already exists, check it with `git remote -v` instead of adding it again.

## What I should understand
Git tracks changes locally. A commit saves a snapshot, and pushing sends commits to GitHub.