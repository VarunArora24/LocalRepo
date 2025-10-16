#All GIT commands for reference
# =========================
# 1. Git Setup & Configuration
# =========================
git config --global user.name "Your Name"
git config --global user.email "you@example.com"
git config --list
git config user.name
git init
git clone <url>

# =========================
# 2. Working with Files
# =========================
git status
git add <file>
git add .
git restore --staged <file>
git restore <file>

# =========================
# 3. Committing Changes
# =========================
git commit -m "message"
git commit -am "message"
git commit --amend -m "new message"
git log
git log --oneline
git log --oneline --graph --all

# =========================
# 4. Branching & Merging
# =========================
git branch
git branch <name>
git checkout <name>
git checkout -b <name>
git merge <branch>
git branch -d <name>
git branch -D <name>
git branch -m <new-name>

# =========================
# 5. Remote Repositories
# =========================
git remote add origin <url>
git remote -v
git push origin <branch>
git push --all origin
git pull origin <branch>
git fetch origin
git remote remove <name>

# =========================
# 6. Stash (Temporary Storage)
# =========================
git stash
git stash apply
git stash list
git stash drop
git stash clear

# =========================
# 7. Undoing & Reverting
# =========================
git reset --soft HEAD~1
git reset --hard HEAD~1
git reset --hard <commit-id>
git revert <commit-id>
git diff
git diff --staged

# =========================
# 8. Tags
# =========================
git tag <name>
git tag -a <name> -m "message"
git tag
git tag -d <name>
git push origin <tag>
git push --tags

# =========================
# 9. Clean Up
# =========================
git clean -f
git clean -fd
git clean -xfd

# =========================
# 10. Info & Help
# =========================
git log <file>
git blame <file>
git show
git branch --show-current
git help <command>

# =========================
# 11. Common Combos
# =========================
# Initialize → Add → Commit
git init && git add . && git commit -m "first commit"

# Clone → Create branch → Push
git clone <url> && git checkout -b new-feature && git push -u origin new-feature
