The Source contains all the files required to run the application.

The tester contains the django project.

Include,Lib and Scripts contain the files created by virtualenv to create django server environment on heroku platform

Usage Instructions:
1. Go to http://lit-harbor-3079.herokuapp.com/pools/.

2. Enter teh text to be compared in the textbox and click submit.

Deployment Instructions:

1.Create a GitHub and Heroku account at www.github.com and www.heroku.com. 

2.Install git and heroku toolbar.

3. Create a git repository named app and copy the files from source to it.

4. Create a new heroku app.
  $ heroku create --stack cedar 

5. Add the git repository to the heroku app.
	$ git add .
	$ git push heroku master

6. Open heroku app.
	$ heroku open
