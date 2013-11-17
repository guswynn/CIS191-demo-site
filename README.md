CIS 191 Project 3
-----------------
For Augustus Wynn

1. My git hook is a shell script that is names so git runs it on my EC2
	server when it recieves a push, after the push is recieved. This hook
	copies files from the push into a publicly accessible folder in the 
	server's home directory called www. From there it used python to start
	a server using the files in www.
2. The python server uses files in the ~/www directory to run a website.
3. A bare repository is one that lacks actual working files of a preject. 
	It only contains the information for the git preject hidden in the folders 	that are usually in the .git directory. In other words a bare repo is one 	that only contains stuff from the .git directory in a normal git repo.     	This is good for a server-side repo because no work is done in a server,  	it just needs the files for people to push and pull from.
