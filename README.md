# Flutter eCommerce App

git init

git branch -M main

git add .
git commit -m "first commit"


# Add your GitHub repository as origin and push
git remote add origin https://github.com/your-username/your-repo.git
git push -u origin main

# Add the original repository as upstream
git remote add upstream https://github.com/other-user/original-repo.git

# To update with changes from the original repo:
git fetch upstream
git checkout main
git merge upstream/main
git push origin main