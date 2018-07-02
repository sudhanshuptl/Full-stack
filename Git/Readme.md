# Git Basics

 ### Clone repository
* ```git clone https://github.com/sudhanshuptl/Full-stack.git```

 ### Check status of commited and uncommited files
* ```git status```

### Add new changes that you want to commit
To move files to staging area
* ```git add space_seperated_file_names```
* To add all files that are changed ```git add .```

 ### Commit selected changes 
```git commit -m "message you want add with this commit"```

### send changes to Github Server
* ```git push```

### Fetch latest changes to local
* ```git pull```

### look all past versions or commits
* ```git log```

## Merge Conflict
let say you made a changes and commit in your local.
and someone else made change to master in server
then before you ```push``` your changes you need to ```pull```
 changes on the server. Now if there is a conflict like changes on servers
 is on exactly same line that of you made in your locals then it create a ``` merge conflict```
 and write both version of that line in a formate so that you can easily see both version and remove one version of the changes. <br />
 
Then to remove the conflict you have to choose which one of two line you need to keep from given two line in conflicted file.
 
 ## Reset Changes
 If you messed it up then you can rest your changes to given commit or to current status of master.
 * ``` git reset --hard <commit hash>```
 * ``` git reset --hard origion/master```
 
 
