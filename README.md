# git-demo
This is tutorial of using git and github.

# commands
1. Clone
    clone any repo from github using { git clone <link> }

2. STATUS
    showing status of files that they are untracked, unmodified, modified or added
    by using {git status}

3. ADD
    add file to server. You can add single files by using {git add <filename.extension>}
    Or, you can add all files together by using {git add .}

4. COMMIT
    final commit with a message to show on server by using {git commit -m "messaage"}

5. PUSH
    push command is used to push from local system to global github server by using {git push origin main}

6. INIT
    used to create new github REPO by using {git init}

7. REMOTE
1. {git remote add origin <link>} for making origin on git repo
2. {git remote -v} to verify
3. {git branch} to check branch
4. {git branch -M main} to rename branch

8. Merge add & commit by using {git commit -am "message"} valid only if we modified only one file

# Branch Commands
1. {git branch} to check branch
2. {git branch -M main} to rename branch
3. {git checkout <branch name>} to navigate
4. {git checkout -b <new branch name>} to create new branch
5. {git branch -d <branch name>} to delete the branch

#Merge two branches
1. {git diff <branch_name>} to compare commits, branches, file & more
2. {git merge <branch_name>} to merge 2 branches
3. CREATE a PR (Pull request)
4. {git pull origin main} used to fetch & download content from remote repo & immediately update the local repo to match that content

# FIXING MISTAKES
~ Staged changes
1. git reset <filename>
2. git reset 

~ Commit changes
1. git reset HEAD~1

# {git log} to check log record

2. {git reset <commithash>} hash is commit code, copy from log records
3. {git reset --hard <commithash>}  to forcefully remove the changes

# author
Winny X