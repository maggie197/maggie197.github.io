1. Open Git Bash in your C:\patch\to\directory directory.
2. Navigate to the directory where your project is located:
```
   cd /path/to/your/directory
```
3. Check the status to see the changes:
```
git status
```
4. Stage the changes (this adds the modified file(s) to the staging area):
```
git add .
```
This will stage all modified files. You can also specify a specific file if needed, like git add <filename>.

5. Commit the changes with a message:
```
git commit -m "Your commit message here"
```
6. Switch to the testing branch:
```
git checkout testing
```
7. Push the changes to the testing branch on GitHub:
```
git push origin testing
```
