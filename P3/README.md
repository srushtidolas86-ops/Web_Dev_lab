# P3 – Feature-branch Git workflow

## Aim
Make changes on a separate branch instead of working directly on main.

## Commands
```bash
git switch -c feature/portfolio-section
# make and save the changes
git status
git add .
git commit -m "Add portfolio section"
git push -u origin feature/portfolio-section
```

After checking the branch on GitHub, create a pull request into `main`. Once it is reviewed and merged:
```bash
git switch main
git pull origin main
```

## What I should understand
A feature branch keeps a piece of work separate until it is ready to merge. Use a clear branch name and a commit message that describes the change.