# BASH CHEATSHEET

### DIRECTORIES

Display path of current working directory : `pwd`

- Change directory to <directory>: `cd <directory>`
- Navigate to parent directory: `cd ..`
- List directory content: `ls`
- List detailed directory contents. Including hidden files:`Ls -la`

### OUTPUT

- Output the contents of <file>: `cat <file>`
- Clear the command line window: `clear`
- Create an alias: `alias <alias>=’<command>’`: for instance `Alias c=’clear’`

### FILES

- Delete file: `rm <file>`
- Delete directory: `rm -r<directory>`
- Rename <file-old> to <file-new>: `mv <file-old> <file-new>`
- Move <file> to <directory>: `mv <file> <directory>`
- Create a file: `touch <file>`

---

# GIT CHEETSHEET

### SETUP & INIT

- initialize an existing directory as a Git repository: `git init`
- retrieve an entire repository from a hosted location via URL: `git clone`

### STAGE & SNAPSHOT

- show modified files in working directory, staged for your next commit: `git status`
- add a file as it looks now to your next commit (stage): `git add <file name>`
- commit your staged content as a new commit snapshot: `git commit -m “<descriptive message>”`

### BRANCH & MERGE

- switch to another branch and check it out into your working directory: `git checkout <branchname></branchname>`
- `git switch <branchname>`
- create a new branch and switch into: `git switch -c <branch name`
