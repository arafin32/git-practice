# Branching & Merging

## Branching
- `git branch` — List, create, or delete branches
- `git checkout` — Switch branches or restore files
- `git switch` — Switch branches (modern alternative)
- `git merge` — Join two or more development histories

## Example
```sh
git branch feature-x
git switch feature-x
# Make changes
git commit -am "Work on feature-x"
git switch main
git merge feature-x
```

## Resolving Conflicts
- Edit conflicting files
- `git add <file>` after resolving
- `git commit` to complete the merge

---

[Next: Remote Repositories](04-remotes.md)
