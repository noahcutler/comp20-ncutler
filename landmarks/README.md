What worked:
	-Has 1 CSS file
	- Retrieves my location via JavaScript navigator.geolocation object
	-Sends my location (latitude, longitude, login) to datastore
	-Retrieves locations of people and historic landmarks within one mile of where i am.
	Displays locations of people in the class on the map. Clicking on a marker will display person's login, and mile(s) away from me in an info window (not always accurate). A unique icon for a person is used(A PICTURE OF ACTOR SEAN WILLIAM SCOTT); all people markers on map use the same icon.
	-Displays historic landmarks within one mile of where i am on the map. Clicking on a marker will display landmark's details in an information window. A unique icon for a landmark is used(ANDREW LLOYD WEBBER); all landmark markers on map use the same icon.
	-Displays my location on the map with unique marker(CLIP-ART GUY WITH CACTUS). 


	
What didn't work:
	-DOES NOT render a polyline connecting my current location and the closest historic landmark from where i am.
	-Classmate distance info is correctly calculated by improperly assigned to each info window.
	-clickling on my name only pulls up my name in an info window

Who helped me:
	Discussed project with: Isaiah Fischer Brown, Brian Taintor, Josh Berl, Russel Gens

	Haversine formula implementation: http://www.htmlgoodies.com/beyond/javascript/calculate-the-distance-between-two-points-in-your-web-apps.html



How much time is spent on this:
	6 or 7 hours