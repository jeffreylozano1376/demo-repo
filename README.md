## UPLOAD LOCAL REPOSITORY TO GITHUB
1. Open command prompt, and change to the project directory<br/>
	```cd <project directory>```
2. Create a new repository in project directory<br/> 
	```git init```
3. Add/track all listed files in directory for staging<br/> 
	```git add .```
4. Commit/finalize the added/tracked files<br/>
	```git commit -m "<title>" -m "<description>"```
5. Add remote location<br/>
	```git remote add origin <remote repo URL>```
6. Push/upload changes to the remote repository(Github)<br/>
	```git push -u origin master```

## CHECK COMMANDS
* Show URL of remote repositories<br/>
	```git remote -v```
* Shows the changes made to a file (not yet commited)<br/>
	```git status```
* Switch to another remote git repository<br/>
	```git remote set-url origin```

## GIT BRANCHING
* create, list, rename, and delete branches<br/>
    ```git branch```
* navigate between branches created by ```git branch```<br/>
    ```git checkout```
* create a new branch<br/>
    ```git checkout -b <name>```
* delete branch<br/>
    ```git branch -d <name>```

## UNDOING IN GIT
* Undo staged changes</br>
    ```git reset```
    ```git reset <file name> ```
* Undo recent commited changes</br>
    ```git reset HEAD~1```
* Shows commit History in reverse chronological order</br>
    ```git log```
* Undo everything within the `git log` History
    ```git reset --hard```
 
 

