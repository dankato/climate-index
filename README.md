Overview: 
Our app receives some user location input, converts the location into longitude and latitidue, and sends this data to the weatherAPI. We getJSON from the weatherAPI, and populate some on-screen table with the data. We compute some score based on the location's weather data, and send some one of five custom queries to the GIPHY API depending on the score. The app will recieve the JSON from the GIPHY API, and print to the screen the GIP. 


What problem are you solving?

Displaying weather and air pollution data to environmentally aware people that also want some humor involved in their data search.

For what Audience?
Environmentally aware people or hypochondriac with a sense of humor.

User stories:
	- As a user, I need to know if I need to wear a mask to go outside today.
	- As a user, I need quick data display for ozone data for my research.
	- As a user, I am thinking about moving to a town, and am concerned about the air quality there.
	- As a user, I want to know how bad my allergies will be today or in some location. 
	- As a weatherman, I want to integrate more humor into my forecast. 

Open Questions:
	- How to translate location: User input (Olney, Maryland) => lon, lat => Send to Weather API 
		- Converts User input City Name into city ID?
			-Zipcode might be the easiest way to do this
		- Which weather data set to start with?
			- Expandable data table
		- How to store user current location?
			- localStorage : an object stored in cookies? 
				- Look at history; 
	- How to hook up the GIPHY and weather?
		- Create some number rating based on a number rated calculated off the weather data input
		- Display weather/air quality score (percentile based or A,B,C,D,E (5 stock GIPs to start - expand if have more time))
			-Display GIF based on quality score
	- What info do we want to display on screen?	
	

	- Should have:
		-Mobile first
	-Nice to Haves: 
		- Auto complete location search bar

