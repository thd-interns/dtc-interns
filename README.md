## Welcome Interns!!!

![](https://media.giphy.com/media/46MDa0sCZ0Fq0/giphy.gif)

***

### Make sure you are logged in to github online

***

### Opening Terminal on Mac
- Open Terminal by using (Command+Space), and then typing Terminal

![](https://media.giphy.com/media/LabvopU8cvupO/giphy.gif)

***

### Set up
- Use the following command to download the master repository
	- `git clone (repo)`
	- `ls`
- Set system-wide settings:
	- `git config user.email "Email on github"`
	- `git config user.name "Name on github"`

![](http://i.imgur.com/OUkLi.gif)

***

### Make a New Branch
- Create a new branch on local
  - `git checkout –b (branch-name)`
 - NOTE: Do not edit to master directly
		- Check what branch you are working on with command
			"git branch"
		
![](https://media.giphy.com/media/m2SlpxfryqLgQ/giphy.gif)

***

### Turning in Changes
- To Do Changes:
	- Do your code changes
	- Enter the command `git status` to see if your edits have been registered
	- Use `git add "filename"` to add changes to the list of files that will be turned in
      - Use `git add .` to add all files
	- Use `git commit -m "Reason for Change"` 
      - Adds all staged files to local branch
	- Finally `git push` to turn in changes
      - Push committed files to remote branch
      		- This may give you an error, just copy and paste the command suggested
	
![](https://i.imgur.com/baZ5y7Z.gif)
