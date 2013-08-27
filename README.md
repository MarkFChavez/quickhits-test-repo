
Title: Online Mall


Proposed technical requirements for this project.

* Amazon AWS / Digital Ocean

* PostgreSQL or MySQL

* Possible languages to use:
	- Ruby (Ruby on Rails)
	- PHP (Laravel)
	- Javascript
		Libraries:
			-jQuery

* Setup: (Possible options)
	a. Application will be API-centric. (Not yet sure)
		- Ruby on Rails as an API? (Using Rack-CORS, Rails-API and Custom Serializers for JSON response)
		- If we are going to use laravel, we might as well use Laravel for our API. Laravel Routes is powerfull enough to handle this and would keep our codes centralized as of the moment
	b. Application will be built using the Laravel framework
	
*Setup Response:
	- If I were to choose between RoR and Laravel for an API-centric approach I'd go for RoR as of the moment. Currently I'm 
	converting some applications to laravel 4 unfortunetly laravel 4 has to many loop holes compared to RoR an example 
	of this is the migration class of laravel, some of the mysql field types are not supported one of them is enum. I'm not sure
	if RoR has the same problem lets ask Mark. Second point why I'll choose RoR as our first option becuase for me it has a 
	better documentation Mark is a living documentation hahaha... but laravel 4 is also an option let's just have a quick 
	brainstorming for this topic 

	c. Application images will be called via API still undecided if our team will create its own API 
	or use existing API's - axel

	d. 	For the application's front-end i suggest to use a MVC javascript framework still undecided
	between Angular.js or Ember.js - axel
		- I think angular would be better for our application. We are not developing a single page application anyway.
		Also, angular has a cleaner coding style than ember. In ember the html tags are enclosed in script tags. The learning curve of Angular is lower than that of Ember. -lance
	
	e. 	For the application's design i'm suggesting that we use bootstraps latest version RC3 customization 
	of the site might be done after we have decided a layout - axel	

