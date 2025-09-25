# Git Workflow Cheat Sheet
# create a new file 
```bash
touch commitsheet.md
```
## 1. Check current branch

```bash
git status
git branch
```
## 2. Create a new feature branch
```bash
git checkout -b your-branch-name
```
## 3. Stage changes
```bash
git add .
# or stage individual files
git add src/pages/HomePage.jsx
```
## 4. Commit changes
```bash
git commit -m "Your commit message"
```
## 5. Push branch to GitHub
```bash
git push origin your-branch-name
```

