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
6. Push/upload changes to the remote Github<br/>
	```git push -u origin master```

## CHECK COMMANDS
* Show URL of remote repositories<br/>
	```git remote -v```
* Shows the changes made to a file (not yet commited)<br/>
	```git status```

## GIT BRANCHING
* create, list, rename, and delete branches<br/>
    ```git branch```
* navigate between branches created by ```git branch```<br/>
    ```git checkout```
* create a new branch<br/>
    ```git checkout -b <name>```
* shows change comparison between 2 versions of code<br/>
    ```git diff```
* merge branches locally<br/>
    ```git merge```
* Push & create a new branch to Github</br>
```git push --set-upstream origin feature-readme-instructions```
