Git config setup
(Optional) change the start up of git bash
	R click on the icon and choose properties
	change "Start in" location
	
Go to your parent project folder
	type $git config --global user.name "your_username"
	type $git config --global user.email "your_useremail"

Go to your parent project folder
	type $git init (project folder name) 
untracked items will show as color red. Use $git add <file_name>  to add file

Go to your parent project folder
	type $git commit -m "your message" this message is the description of what your committing (be clear)
	
Commands:
	$git status       / tells you about untracked,uncommitted, or modified files (your local only)
	$git log          / keeps track of all your commits (important to have clear messages)
				      / when the log gets very long, to exit press shift+zz
	$git log --online / condenses the info on screen			 
 
In order to commit to Remote share (GITHUB) you need to create SSH key or HTTPS

To add your remote repo $git remote add <tagname of repo> <cloned url>

Then you can push $git push <tagname of repo> <branch>
















