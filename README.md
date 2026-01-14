# DCSG2003_g22

Step-by-step guide Commit/Push

cd ~/DCSG2003_g22
git config --local user.name "github_Eskild"
git config --local user.email "eskildambakk12@gmail.com"

cd ~/DCSG2003_g22
git config --local user.name "github_Simen"
git config --local user.email "simen.walde@gmail.com"

Rules
1. Always pull before you start work
2. Always work on your own branch
3. Before you commit, set your name/email to your user
4. When you push, use your own remote
  Eskild pushes to origin
  Simen pushes to simen

Step 1 (go to repo):
  cd ~/DCSG2003_g22

Step 2 (pull latest changes):
  git checkout main
  git pull --rebase

Step 3(create branch):
  Eskild:
    git checkout -b eskild/<short-description>
  Simen: 
    git checkout -b simen/<short-description>

Step 4(set identity):

Step 5():
  git add .
