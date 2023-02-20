# Git tutorial

## Git Commands

### Build Git in a folder

> git init

### Add files to stage

> git add .

### Commit all files in stage

> git commit -m "message about commit"

### Removing files

```
remove a file from the fold which does not happen in the stage. Update the stage by add command and then commit. So use git rm that removes the file in folder and stage.
```

> git rm filename.txt

## clone github repository 

> git clone url

### Fetch updates from github

> 	git fetch     // download update from gihub, but not a update on local directory.
> 	
> 	git branch -vv      //check the master status
> 	
> 	git merge origin/main  //update local directory.

### pull = fetch+merge(update the working directory)

> 	git pull creates a non-linear branch 
> 	git pull --rebase   //create a linear branch

### push
git add 
git commit
>git push






