

####Starting a new project

1. Navigate to your working directory for class. Ex:
	```
	$ cd Sites
	```

2. Start a python simple server.
	```
	$ python -m SimpleHTTPServer 8000
	```


3. Clone a copy of the News Apps Template from Chris' Git page, and rename it
	```
	$ git clone https://github.com/chriscanipe/web-app-template-simple.git new-project-name
	```


####Saving to YOUR repository:

1. Create a new repo on YOUR Git page
Open your Git page, create and name a new repository.

2. Remove the original ORIGIN (which links to Chris' Git page)
	```
	$ git remote rm origin
	```

3. Add YOUR origin to the repository
	```
	$ git remote add origin [address copied from your newly-created repo]
	```

4. Add all untracked files to the repository.
	```
	$ git add .
	```
	OR 
	```
	$git add -A
	```

5. Commit your changes.
	```
	$ git commit -am "Describe your changes here"
	```

6. Push to your new repository.
	```
	$ git push origin master
	```

###Git Markdown Cheatsheet:
https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet
