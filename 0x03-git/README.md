# GIT COMMANDS
1. **git clone**   
Usage: git clone [url]  
This command is used to obtain a repository from an existing URL.
2. **git add**  
Usage: git add [file]  
This command adds a file to the staging area.  
Usage: git add *  
This command adds one or more to the staging area.
3. **git init**  
Usage: git init [repository name]  
This command is used to start a new repository.
4. **git diff**  
Usage: git diff  
This command shows the file differences which are not yet staged.  
Usage: git diff –staged
This command shows the differences between the files in the staging area and the latest version present.  
Usage: git diff [first branch] [second branch]  
This command shows the differences between the two branches mentioned.
5. **git reset**  
Usage: git reset [file]  
This command unstages the file, but it preserves the file contents.  
Usage: git reset [commit]   
This command undoes all the commits after the specified commit and preserves the changes locally.  
Usage: git reset –hard [commit]  
This command discards all history and goes back to the specified commit.
6. **git rm**  
Usage: git rm [file]  
This command deletes the file from your working directory and stages the deletion.
7. **git commit**  
Usage: git commit -m “[ Type in the commit message]”  
This command records or snapshots the file permanently in the version history.  
Usage: git commit -a  
This command commits any files you’ve added with the git add command and also commits any files you’ve changed since then.  
8. **git push**  
Usage: git push [variable name] master  
This command sends the committed changes of master branch to your remote repository.  
Usage: git push [variable name] [branch]  
This command sends the branch commits to your remote repository.  
Usage: git push –all [variable name]  
This command pushes all branches to your remote repository.
9. **git branch**  
Usage: git branch   
This command lists all the local branches in the current repository.  
Usage: git branch [branch name]  
This command creates a new branch.  
Usage: git branch -d [branch name]  
This command deletes the feature branch.
10. **git checkout**  
Usage: git checkout [branch name]  
This command is used to switch from one branch to another.  
Usage: git checkout -b [branch name]  
This command creates a new branch and also switches to it.
11. **git merge**  
Usage: git merge [branch name]  
This command merges the specified branch’s history into the current branch.
12. **git status**  
Usage: git status  
This command lists all the files that have to be committed.
13. **git config**  
Usage: git config –global user.name “[name]”    
Usage: git config –global user.email “[email address]”  
This command sets the author name and email address respectively to be used with your commits.
14. **git pull**  
Usage: git pull [Repository Link]  
This command fetches and merges changes on the remote server to your working directory.
