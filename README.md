# Git-Github-Studies

## Get Git
You can download git from: https://www.git-scm.com/

### Basic commands

#### Config
git config --user.name "Your Name"
git config --user.email "your_email@example.com"

####Get documentation about of the command:
git command -h

####Init a repo
git init

####Get repo status
git status

####Track and untrack files

- track:
git add filename

- untrack
git rm --cached filename


####Commit
git commit -m "message about the change"

####Change files and view difference
git diff

You don't want to commit the differences and want to restore
git restore --stagged filename

You want to skip the tracking step and go straight to commit
git commit -a -m "message about the change"

####Delete files
git rm "filename"

####Restore file
git restore "filename"

####Rename file
git mv "oldfilename" "newfilename"

####View commit history with git log
git log --oneline

####Amend commit
git commit -a -m "message corrected" --amend

####View changes in commits
git log -p

####Branches
 create a new branch
 git branch NameBranch
 
 see existent branchs
 git branch
 
 switch to other branch
 git switch NameBranch
 
 ####Merge branches
 git merge -m "message for the merge" NameBranch
 
 ####Delete a branch
 git branch -d NameBranch
 
 
