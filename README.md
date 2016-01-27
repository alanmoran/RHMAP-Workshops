# RHMAP-Workshops

## Workshop 1 - My First App

* Create a new project using any of the *Hello World* templates
* Modify the **client** to do the follow:
	* Add an number input that will accept an age
	* Modify view logic to handle age
	* Pass an object that contains both name and age to cloud
	* Update $fh.cloud to use a POST 
* Modify the **cloud** to do the follow:
	*  Update the POST hello route to check age
	* If age is over 25 return a message to say so
	* If age is under 25 return a message to say so
	* Return a formatted message that the client can handle
	
### What did you learn?
* Creating a project from a template
* Using built in studio editor
* Deploying Cloud 
* Using the studio app preview
* Using Google Chrome for debugging
* Layout of Node.js Cloud Applications
* ExpressJS
* Client API's - $fh.cloud	
	
### Solutions:
* [Client](https://github.com/alanmoran/RHMAP-workshop1-client)
* [Cloud](https://github.com/alanmoran/RHMAP-workshop1-cloud)

## Workshop 2 - MBaaS API's
* Create a new project using any of the *Hello World* templates
* Modify the **client** to do the follow:
	* Add new input fields to accept - Name, Job Tite and Country
	* Modify view logic to handle these new fields
	* Pass an object that contains all these fields to the cloud app
	* Update $fh.cloud to use a POST and use a route called database/add
* Modify the **cloud** to do the follow:
	* Create new route called database/add
	* Save all the details to Mongo using $fh.db
	* If the save works return an "ok message to the app"
	* If there is an error return a "friendly error" to the client
	
### What did you learn?
* ExpressJS - Creating new Routes
* Client API's - $fh.cloud	
* Cloud API's $fh.db
* Use of the docs site
* Data Browser
* Angular - Basic

### Solutions:
* [Client](https://github.com/alanmoran/RHMAP-workshop2-client)
* [Cloud](https://github.com/alanmoran/RHMAP-workshop2-cloud)


##Demo - Form's & Form's API    
            
##Demo - Push Notifications (iOS)
