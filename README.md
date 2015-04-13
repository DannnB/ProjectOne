*Written by [DannnnB](https://github.com/DannnB)*
#### Basic CMD 
1. `cd ..` (up dir)
2. `ls` (from git bash) or `dir` (from CMD/Windows) (list files in dir)
3. `cd Users` (change to dir)

#### Git Shell & CMD

1. `git clone` (copies a git from a link eg. http://github.com/username/project)
2. `git status` (diffrence between github and you)
3. `git add` (adds new files/changes by file name. put into project. git add index.html)
4. `git add .` (add all files)
5. `git add -A` (add all files)
6. `git commit` (locked in. Ready to be uploaded. -m "a message of changes")
7. `git push` (take all committed files and uploads/pushes to github.com)
8. `git pull` (pulls latest git commit.)
- `git` (list all commands)

####Simple Workflow
1. 
2. `git pull`
3. "make changes"
4. `git add index.html` or ``
5. `git commit -m "message for commit"` (a file or all files)
6. `git push`

#### Merge Conflict

1. manually merge lines at helper lines
2. git add -A
3. git commit

#### Stuck in cmd after commit or during one

- ESC (then) :wq

#### Branching

- "All in your working DIR"

1. git pull (latest files)
2. git branch (shows master + other branches)
3. git branch name-of-branch (copies MASTER)
4. git checkout name-of-branch (changes to branch. Not going to mess with Master.)
5. git add -A (or) git add filename.html (add edited files)
6. git branch (branch selection)
7. git checkout master (back to master)
8. git pull (check to see if anyone else has updated master)
9. git checkout name-of-branch
10. git merge master (merges to master branch)

- Begin by doing a git pull to get the latest content on your master branch
- Run "git branch your-feature-name" to make a git branch
- Code in your changes, add and commit the files
- Pull the master branch again and merge it with your new branch
- Push the branch up to github and submit it as a pull request
- That pull request can now receive comments and code discussion, as well as accept new commits before being merged in with the master branch


#### CMDER
######Tab manipulation

- Ctrl + ` : Global Summon from taskbar
- Win + Alt + p : Preferences (Or right click on title bar)
- Ctrl + t : New tab dialog (maybe you want to open cmd as admin?)
- Ctrl + w : Close tab
- Shift + Alt + number : Fast new tab:
- CMD
- PowerShell
- Alt + Enter : Fullscreen
######Shell

- Shift + Up : Traverse up in directory structure (lovely feature!)
- End, Home, Ctrl : Traverse text as usual on Windows
- Ctrl + r : History search
- Shift + mouse : Select and copy text from buffer
- Right click / Ctrl + Shift + v : Paste text

###### LearnCode.academy
[YouTube Coding](https://www.youtube.com/channel/UCVTlvUkGslCV_h-nSAId8Sw)
