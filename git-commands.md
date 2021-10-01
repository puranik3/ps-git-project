# Getting started with Git and GitHub

1. Create a repository for the project in GitHub / BitBucket / GitLab...
2. In the local system, we ask Git the project - we switch to the project folder and we issue the command
```
git init
```
3. Issue the command to check the status of tracked files, commits etc.
```
git status
```
4. To stage files and folders (Git "starts" tracking - it goes through the contents of your files and folders and "indexes" them - makes a copy of the content)
```
git add <file> <folder> ...
```
NOTE: You can ask git to track everything in your project this way
```
git add .
```
