#`Git Guide`
######Hopefully this will fix some headaches! It took me ages to figure out how to fx things and get it all running by using many, many forums. Mainly for my own reference but might help others.
*Written by [DannnnB](https://github.com/DannnB)* 
## Basic CMD 
1. `cd ..` (Up dir)
2. `ls` (From git bash) or `dir` (From CMD/Windows) (List files in dir)
3. `cd Users` (Change to dir)

## Git Shell & CMD

1. `git clone` (Copies a git from a link eg. http://github.com/username/project)
2. `git status` (Difference between GitHub and you)
3. `git add` (Adds new files/changes by file name into repo commit. `git add index.html`)
4. `git add .` (Adds all files)
5. `git add -A` (Adds all files)
6. `git commit` (Locked in. Ready to be uploaded. Use: `git commit -m "a message of changes`)
7. `git push` (Take all committed files and uploads/pushes to github.com)
8. `git pull` (Pulls latest git commit)
- `git` (List all commands)

## Simple Workflow
1. "start"
2. `git pull`
3. "make changes"
4. `git add index.html` or `git add -A` (adds all)
5. `git commit -m "message for commit"` (a file or all files)
6. `git push`

## Merge Conflict

1. Manually merge conflict lines at helper lines
2. `git add -A`
3. `git commit`

###### Stuck in cmd after commit or during one

- ESC (then) `:wq`

## Branching

- "All in your working DIR"

1. `git pull` (latest files)
2. `git branch` (shows master + other branches)
3. `git branch name-of-branch` (copies MASTER)
4. `git checkout name-of-branch` (changes to branch. Not going to mess with Master.)
5. `git add -A` (or) git add filename.html (add edited files)
6. `git branch` (branch selection)
7. `git checkout` master (back to master)
8. `git pull` (check to see if anyone else has updated master)
9. `git checkout name-of-branch`
10. `git merge master` (merges to master branch)
- On GitHub submit it as pull request
- Enables comments, can add commits if needed before merge eg code changes.


## CMDER
##Tab manipulation

- **Ctrl + `** : Global Summon from taskbar
- **Win + Alt + p** : Preferences
- **Ctrl + t** : New tab dialog
- **Ctrl + w** : Close tab
- **Shift + Alt + number** : Fast new tab
- **Alt + Enter : Fullscreen**
- **Shift + Up** : Traverse up in directory structure
- **End, Home, Ctrl** : Traverse text as usual on Windows
- **Ctrl + r** : History search
- **Shift + mouse** : Select and copy text from buffer
- **Right click / Ctrl + Shift + v** : Paste text

###### LearnCode.academy
[YouTube Coding](https://www.youtube.com/channel/UCVTlvUkGslCV_h-nSAId8Sw)
