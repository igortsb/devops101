# Set up a new Git repository and create a dev branch for 'new-project'

1. Create a 'development' branch and move to it:
```
git branch development
git checkout development
```
2. Update the code, save changes (Ctrl+S), and add the changes to the index:
```
git add .
```
3. Commit changes in 'development' branch with your message describing changes:
```
git commit -m "<your  message>"
```
> **Note:** Jira Ticket is usually used in 'your  message' to refer the changes made.

4. Push changes to 'development' branch:
```
git push
```
5. Check if the changes merged successfully:
```
git status
```
6. Merge 'development' branch to 'origin/main' branch
```
git checkout main
git pull origin main
git merge development
git push origin main
```