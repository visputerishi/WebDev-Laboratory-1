# P3: Feature-Branch Git Workflow

## Aim
To make a change on a feature branch, commit it, and merge it into the main branch.

## Workflow
```sh
git switch -c feature/portfolio-labs
# Make and review the lab changes
git status
git add README.md WebDevelopment
git commit -m "Complete web development laboratory exercises"
git switch main
git merge --ff-only feature/portfolio-labs
```

## Result
The laboratory work is prepared as a self-contained feature branch change that can be reviewed and fast-forwarded into `main`.
