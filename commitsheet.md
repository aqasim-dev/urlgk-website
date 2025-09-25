# Git Workflow Cheat Sheet
INITIAL SETUP (Developer A) to create git repository
```bash
git init
git remote add origin <REPO_URL>
touch README.md
git add .
git commit -m "Initial commit"
git push -u origin main
```
```bash
# clone the repository
git clone <REPO_URL>
cd <repo>
```
```bash
# create a new file
touch commitsheet.md  
```


```bash
# 1. Check current branch
git status
git branch

# 2. Create and switch a new feature branch
git checkout -b your-branch-name
git switch branch name

# 3. Stage changes
git add .
# or stage individual files
git add src/pages/HomePage.jsx

# 4. Commit changes
git commit -m "Your commit message"

# 5. Push branch to GitHub
git push -u origin your-branch-name

# 6.clean up or delete feature branch/tasks
git branch -d feature/your-task-name
git push origin --delete feature/your-task-name

# 7. see all remote branches
git fetch --all
git branch -r

# 8. compare branches
git diff main..feature/branch-name

# 9. rename branch and delete old one
git branch -m old-branch-name new-branch-name
git push origin new-branch-name
git push origin --delete old-branch-name
```
# all commands to make changes in the default branch
```bash
git switch default-branch
git add .
git commit -m "Your commit message" # required to track history
# make changes in any file
git pull origin default-branch 
git push origin default-branch
```


