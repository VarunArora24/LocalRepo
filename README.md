#All GIT commands for reference
# =========================
# 1. Git Setup & Configuration
# =========================
<br>git config --global user.name "Your Name"
<br>git config --global user.email "you@example.com"
<br>git config --list
<br>git config user.name
<br>git init
<br>git clone <url>

# =========================
# 2. Working with Files
# =========================
<br>git status
<br>git add <file>
<br>git add .
<br>git restore --staged <file>
<br>git restore <file>

# =========================
# 3. Committing Changes
# =========================
<br>git commit -m "message"

# =========================
# 4. Branching & Merging
# =========================
<br>git branch
<br>git branch <name>
<br>git merge <branch>
<br>git branch -M <new-name>

# =========================
# 5. Remote Repositories
# =========================
<br>git remote add origin <url>
<br>git remote -v
<br>git push origin <branch>
<br>git push --all origin
<br>git pull origin <branch>
<br>git fetch origin
<br>git remote remove <name>
<br>
# =========================
# 6. Clean Up
# =========================
<br>git clean -f
<br>git clean -fd
<br>git clean -xfd

# =========================
# 7. Info & Help
# =========================
<br>git log <file>
<br>git blame <file>
<br>git show
<br>git branch --show-current
<br>git help <command>

# =========================
# 8. Common Combos
# =========================
# Initialize → Add → Commit
<br>git init && git add . && git commit -m "first commit"

# Clone → Create branch → Push
<br>git clone <url> && git checkout -b new-feature && git push -u origin new-feature
varun muje welcome kar ki tune muje saare codes dediye free mei 
