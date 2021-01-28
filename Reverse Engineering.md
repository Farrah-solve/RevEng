

## Develop\config\middleware
\isAuthenticated.js: 
	This file handles registered and unregistered users and redirects them accordingly.  

## Develop\config
\config.json: 
	Acts as the configuration for mySQL databases.  

\passport.js: 
	This runs upon loading the page and serves as a method for checking if a user is registered, has a valid email and unique username.   

## Develop\models
\index.js: 
	Gathers required packages & handles setup. This file connects to the config.json file to execute connection settings.

\user.js: 
	Creates our user account or information. This JavaScript can use bcryptjs to hash out the password in the database to protect user’s login account info. 

## Develop\public\js
\login.js
	Gets the data from the login form. This information is passed through as a function and If the user has logged in before or registered than that user is redirected to sign in.

\members.js
	This js file looks up the information about the logged in user and returns the values of the member id.

\signup.js
	This js file directs the user to a sign up page for creating an account.

## Develop\public
\login.html
	This is the html file used for the login page. The page provides the form for input requested of the user to enter as they did upon sign up. 

\members.html
	This is the html file used for the members’ page.

\signup.html
	This is the html file used for the signup page. Requests user input for user data/id.

## Develop\routes
\api-routes.js
       The file defines what API routes are available for use in the application. 

\html-routes.js
	This file handles the routing to the correct html files.

## Develop\server.js: 
    This file is executed through a window to begin running on our server and executing the code.

## Develop\package.json: 
	This file lists all the packages and dependencies necessary to run the code and have it function correctly. Without these packages installed the code will not function.