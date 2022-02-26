# Project REST-Rant

REST-Rant is an app where users can review restaurants.

As an end user I need form so I can add a restaurant

Wireframe start

Color palette chosen randomly with Coolers.co #ADA8B6, #FFEEDB, #4C3B4D, #A53860, #61C9A8


|Method     |Path       |Purpose
|-----------|-----------|-------------------
|GET    	|/      	|Home page
|GET    	|/places	|Places index page
|POST   	|/places	Create new place
|GET    	|/places/new	Form page for creating a new place
|GET    	|/places/:id	Details about a particular place
|PUT    	|/places/:id	Update a particular place
|GET    	|/places/:id/edit	Form page for editing an existing place
|DELETE 	|/places/:id	Delete a particular place
|POST   	|/places/:id/rant	Create a rant (comment) about a particular place
|DELETE 	|/places/:id/rant/:rantId	Delete a rant (comment) about a particular place
|GET    	|*	404 page (matches any route not defined above)
