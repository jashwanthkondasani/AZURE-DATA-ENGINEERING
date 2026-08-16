<!-- git status
 -->
# START NEW WORK
git checkout main
git pull origin main

# GO TO FEATURE
git checkout feature

# WORK ON FILES
# SAVE FILES

# CHECK
git status
git diff

# COMMIT
git add .
git commit -m "Describe my changes"

# PUSH
git push origin feature

# GITHUB
# feature → main
# Squash and merge

# AFTER SQUASH & MERGE
git checkout main
git pull origin main

# DELETE OLD FEATURE
git branch -D feature
git push origin --delete feature

# CREATE FRESH FEATURE
git checkout -b feature
git push -u origin feature

<!-- befpre -->
git checkout main
git pull origin main
<!-- before pushing -->
git status
git add .
git commit -m "your message"
git push origin feature

<!-- after squash merge -->
git checkout main
git pull origin main
git branch -D feature
git push origin --delete feature
git checkout -b feature
git push -u origin feature

        START
          ↓
     checkout main
          ↓
      pull main
          ↓
     create feature
          ↓
       DO WORK
          ↓
       git add
          ↓
      git commit
          ↓
      git push
          ↓
    GitHub PR
          ↓
   SQUASH & MERGE
          ↓
     checkout main
          ↓
       pull main
          ↓
   DELETE OLD FEATURE
          ↓
   CREATE NEW FEATURE
          ↓
       NEXT WORK