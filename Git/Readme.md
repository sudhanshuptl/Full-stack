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


Then to remove the conflict you have to choose which one of two line you need to keep from given two line in conflicted file.
 
 ## Reset Changes
 If you messed it up then you can rest your changes to given commit or to current status of master.
 * ``` git reset --hard <commit hash>```
 * ``` git reset --hard origion/master```
 
 
 ## Git Branches
 * To See all available branches ```git branch```
 * To create new Branch ```git branch new_branch_name```
 * To edit in given branch, we needto  change pointer to new branch <br \>
 ``` git checkout branch_name```
 
 ## git checkout
 * **switch between branch** in local repository For instance <br />
 ```git checkout exists_branch_to_switch```
 * You can also create new branch and switch out in throught this case with -b <br />
    ```git checkout -b new_branch_to_switch```
 * restore file from x rev **restoring state of file to last commit**<br />
 ```git checkout rev file_to_restore```
 
 ## Merge to new_Branch to master
   * ```git merge branch_name```
 
 ## Push your new branch as new branch to Github
 * ```git push --set-upstream origion  branch_name```
  
 ## Merge Conflict
let say you made a changes and commit in your local.
and someone else made change to master in server
then before you ```push``` your changes you need to ```pull```
 changes on the server. Now if there is a conflict like changes on servers
 is on exactly same line that of you made in your locals then it create a ``` merge conflict```
 and write both version of that line in a formate so that you can easily see both version and remove one version of the changes. <br />
 
 