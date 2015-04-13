#### Basic CMD 
cd .. (up dir)
ls/dir (list files in dir)
cd Users (into dir)
#### Git Shell/CMD
git clone (copies a git from a link eg. http://github.com/username/project)
"All in your working DIR"
git status (diffrence between github and you)
git add (adds new files/changes by file name. put into project. git add index.html)
git add . (add all files)
git add -A (add all files)
git commit (locked in. Ready to be uploaded. -m "a message of changes")
git push (take all committed files and uploads/pushes to github.com)
git pull (pulls latest git commit.)

git (list all commands)

#### Workflow
"start"
git pull
"make changes"
add
commit a file or all files
git push
#### Merge Conflict

manually merge lines at helper lines
git add -A
git commit

#### Stuck in cmd after commit or during one

ESC (then) :wq

#### Branching
"All in your working DIR"
git pull (latest files)
git branch (shows master + other branches)
git branch name-of-branch (copies MASTER)
git checkout name-of-branch (changes to branch. Not going to mess with Master.)

- Begin by doing a git pull to get the latest content on your master branch
- Run "git branch your-feature-name" to make a git branch
- Code in your changes, add and commit the files
- Pull the master branch again and merge it with your new branch
- Push the branch up to github and submit it as a pull request
- That pull request can now receive comments and code discussion, as well as accept new commits before being merged in with the master branch


#### CMDER
--Tab manipulation--

Ctrl + ` : Global Summon from taskbar
Win + Alt + p : Preferences (Or right click on title bar)
Ctrl + t : New tab dialog (maybe you want to open cmd as admin?)
Ctrl + w : Close tab
Shift + Alt + number : Fast new tab:
1. CMD
2. PowerShell
Alt + Enter : Fullscreen
--Shell--

Shift + Up : Traverse up in directory structure (lovely feature!)
End, Home, Ctrl : Traverse text as usual on Windows
Ctrl + r : History search
Shift + mouse : Select and copy text from buffer
Right click / Ctrl + Shift + v : Paste text