#Mullen Lowe Tumblr Starter Project
##Using Peak

###Installation

1. Open Terminal or and Command Line and enter the following:

	```
	$ npm install peak -g
	```

2. Move your current directory to wherever you plan on building your project:

	```
	$ cd /local-folder
	```

3. Generate your peak project where `your-theme-name` is the path of the folder you'd like to create.

	```
	$ peak new your-theme-name -b your-blog-name -e your-tumblr-user -p 'your-password' -i "index.html"
	```

	###### Parameter Definitions:
	- b = Blog Name (without [.tumblr.com])
	- e = Your Tumblr Account's email address
	- p = Your Tumblr Account password
	- i = The main project file (you will replace this later)

4. Move the files in the `peak-tumblr-boilerplate` folder into your new project folder, then remove the empty boilerpate folder:

	```
	$ mv peak-tumblr-boilerplate/* your-theme-name/
	$ rm -R peak-tumblr-boilerplate/
	```

5. In Terminal, cd to your new project folder and run the project.

  ```
  $ cd your-theme-name
  $ peak watch
  ```

6. You should be able to now work on your Tumblr site locally at [localhost:1111](http://localhost:1111)