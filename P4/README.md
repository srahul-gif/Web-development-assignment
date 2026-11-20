# P4 – GitHub README and Version Tagging

## Aim
To create project documentation, connect a local Git repository to GitHub and create a version tag.

## Commands

```bash
git add README.md
git commit -m "Add README file"
git tag -a v1.0 -m "First version"
git tag
git remote -v
git push -u origin main
git push origin v1.0
```

## Description

- `git add README.md` stages the README file.
- `git commit -m` saves the documentation.
- `git tag -a v1.0` creates an annotated version tag.
- `git tag` lists available tags.
- `git remote -v` displays connected remote repositories.
- `git push -u origin main` uploads the main branch.
- `git push origin v1.0` uploads the version tag to GitHub.

## Result
Successfully created project documentation, connected the local repository to GitHub and uploaded version tag v1.0.