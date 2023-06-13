# Git  workflow

git checkout main
git checkout -b develop
git checkout -b feature_branch

##  -> work happens on feature branch ...
###   -> after you are done with the feature branch

git checkout develop
git merge feature_branch
git checkout main
git merge develop
git branch -d feature_branch
