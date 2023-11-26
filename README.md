Set up a new Git repository and create a a dev branch for 'new-project

1. Crete a 'new-project' directory in your env

2. Move to the 'new-project' directory

cd new-project

3. Intialize a new public git repo in the 'new-project' directory running:

git init

4. Create a 'README.md' file in 'new-project' directory

echo README.md

5. Stage the chnages

git add .

6. Commit the changes with 'init' message

git commit -m "init"

7. Create a 'development' branch and move to it

git branch development
git checkout development

8. Add instructions to 'README.md'

git add README.md

9. Commit changes in 'development' branch

git commit -m "step 8 added"

10. Merge chnages to 'master' branch

git checkout master
git merge developemnt

11. Check status

git status

12. Delete 'development' branch

git branch -d development