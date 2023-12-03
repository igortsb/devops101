Set up a new Git repository and create a dev branch for 'new-project

1. Create a 'development' branch and move to it

git branch development
git checkout development

2. Update the code if necessary, and add changes to the index

git add .

3. Commit changes in 'development' branch with your message describing changes

git commit -m "<your message>"

4. Push chnages to 'origin/main' branch

git checkout master
git merge developemnt

5. Check if the changes merged successfully

git status