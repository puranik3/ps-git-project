# Getting started with Git and GitHub

1. Create a repository for the project in GitHub / BitBucket / GitLab etc. - we get a "remote url" (eg. git@github.com:puranik3/ps-git-project.git)
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
__NOTE__: You can ask git to track everything in your project this way
```
git add .
```
__NOTE__: Even after we stage a file (git add), if we change the files, we yet again need to run git add
5. We commit like so
```
git commit -m "commit message"
```
You can amend the recent commit this way
```
git commit --amend -m "new commit message"
```
6. View all the commits
```
git log
```
7. Use git remote to tie up your local folder to GitHub repo. For example...
```
git remote add origin git@github.com:puranik3/ps-git-project.git
```
8. When we start a git project, we get 1 branch - master
9. To tie up the local current branch (master branch) to the remote master branch, we do the following
```
git push --set-upstream origin master
```
