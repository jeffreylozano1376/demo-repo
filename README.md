## UPLOAD REPOSITORY TO GITHUB
1. Open command prompt, and change to the project directory
	$ cd <project directory>
2. Create a new repository in project directory
	$ git init
3. Add/track all listed files to repository
	$ git add .
4. Commit the files
	$ git commit -m "adding files"
5. Add remote location
	$ git remote add origin <remote repo URL>
6. Push commited files
	$ git push -u origin master

## CHECK COMMANDS
** Show URL of remote repositories
	$ git remote -v
** Shows the changes made to a file (not yet commited)
	$ git status
