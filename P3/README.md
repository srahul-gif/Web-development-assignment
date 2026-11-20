# P3 – Feature Branch Git Workflow

## Aim
To understand Git branching, create a feature branch, make changes, commit them and merge the branch into the main branch.

## Commands

```bash
git branch --show-current
git switch -c feature-portfolio
git branch
echo "Feature branch workflow completed" > feature-demo.txt
git add .
git commit -m "Add feature branch demonstration"
git switch main
git merge feature-portfolio
git log --oneline --graph --all
```

## Description

- `git branch --show-current` displays the current branch.
- `git switch -c feature-portfolio` creates and switches to a new feature branch.
- `git branch` lists available branches.
- `echo` creates a demonstration file with sample content.
- `git add .` stages the changes.
- `git commit -m` saves the changes in the feature branch.
- `git switch main` switches back to the main branch.
- `git merge feature-portfolio` merges the feature branch into main.
- `git log --oneline --graph --all` displays the commit history of all branches.

## Result
Successfully created a feature branch, committed changes and merged the feature branch into the main branch.