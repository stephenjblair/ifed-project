# Interactive Front End Development Project 02  
This project is called 'Party Safari'. A simple, one-page application that integrates the Google Maps and Google Places APIs to allow the user to plan a night out in a city of their choice.

[Party Safari App](src="img/partsafari.png")

## User Stories

1.	As a user, I want to be able to choose any city around the world to plan a night out.
2.	As a user, I want to be presented with various points of interest that I might need to see to make my night a success. This should include the obvious bars and clubs that I may visit and also various shopping options, beauty salons and hair salons should I want to prepare my look for my night. I also want to be able to see hotels if I am travelling to that city and wish to stay over.
3.	As I user, once I have chosen the country and city I am interested in, as I select my point of interest I want to see these populated on the map and the results presented in a simple list.
4.	As a user, I want a clean and simple interface which is easy to navigate.


## Wireframes
A simple PDF file has been uploaded within the UX directory to show a simple wireframe of the site.

## UX and Design
I used CSS flexbox for layout for ease of making elements responsive across devices. I wanted the layout and design for this site to be quite stripped back and simple. I wanted to use colours that would support the idea of a 'safari' so opted for camel coloured tones, blended with lighter gradients of black and white. Ideas for colour schemes and the corresponding hex code values I would need were obtained from [Palleton](http://paletton.com/#uid=1000u0kllllaFw0g0qFqFg0w0aF).  
I decided that the map should by styled as a night time theme to fit in with the nightlife concept of site and also the colour scheme I had already chosen. I did this by amending the styles within the initMap function.


## Features
### Existing Features

* Drop down select menu to choose country.
* Auto zoom to country of interest.
* Input element to enter city, which autocompletes via the Google Maps API.
* Auto zoom to central point of city of interest.
* Point of interest select menu.
* Auto populate markers on map for point of area chosen.
* Auto populate results of POI into a separate list in the results box.

## Features Left to Implement

* Further API integration to show listings and events for venues.
* Ability to purchase tickets for events.
* Sign up to newsletter for upcoming events and ticket offers in cities of interest.
* Integration of booking.com API to allow for hotel bookings directly from the site.
* Integration of Air BNB API to show further accommodation options, beyond the hotels listed, with ability to book.

## Technologies Used
* [HTML5](https://en.wikipedia.org/wiki/HTML5) - For site layout and structure.
* [CSS3](https://en.wikipedia.org/wiki/Cascading_Style_Sheets)	- For design and styling of the site. Flex-box was used for layout and responsiveness.
* [Google Fonts](https://fonts.google.com/) - 'Major Mono Display' was used was used to fit with the styling of the site.
* [Palleton](http://paletton.com/#uid=1000u0kllllaFw0g0qFqFg0w0aF) - To assist with colour schemes.
* [Javascript](https://en.wikipedia.org/wiki/JavaScript) - Site function and use of APIs.
* [Google Maps API](https://developers.google.com/maps/documentation/javascript/tutorial) - For map and location features.
* [Google Places API](https://developers.google.com/places/web-service/intro) - For points of interest, markers and list results.
* [Microsoft Powerpoint](https://en.wikipedia.org/wiki/Microsoft_PowerPoint) - For the site wireframe.
* [GitHub](https://www.github.com) - For version control.


## Testing
General Testing
* [HTML](https://validator.w3.org/) – W3 schools HTML validator. To check for syntax errors.

* Result
Warning: Consider avoiding viewport values that prevent users from resizing documents.

From line 5, column 5; to line 5, column 92

F-8">↩    <meta name="viewport" content="width=device-width, initial-scale=1.0, user-scalable=no">↩
*Removed to allow for user resizing*

* Result

Error: An img element must have an alt attribute, except under certain conditions. For details, consult guidance on providing text alternatives for images.

From line 14, column 31; to line 14, column 71
*Amended by providing suitable alt for image*

* Result

Error: Stray end tag select.
From line 43, column 1; to line 43, column 9

 a City">↩</select>↩</div>
*Amended by closing tag*

* [CSS](https://jigsaw.w3.org/css-validator/) – W3 Schools CSS validator. To check for syntax errors. No errors were found.
* [JavaScript](https://developers.google.com/web/tools/chrome-devtools/console/) – console via Chrome developer Tools. To check for any scripting errors.
* [Google Chrome Developer Tools](https://developers.google.com/web/tools/chrome-devtools/) - To check cross-device compatibility. To trial and error styles and design options in the quickest manner possible.
* [Responsinator](http://www.responsinator.com/?url=http%3A%2F%2Fstephenjblair.github.io%2Fucd-project) - To further check cross device compatibility.
* [JS Hint](https://www.jshint.com) - To detect errors and potential problems within the Javascript code.

* Result

Metrics
There are 17 functions in this file.

Function with the largest signature take 2 arguments, while the median is 0.

Largest function has 25 statements in it, while the median is 3.

The most complex function has a cyclomatic complexity value of 7 while the median is 1.

Two warnings
65	['uk'] is better written in dot notation.
66	['uk'] is better written in dot notation.

Two undefined variables
64	google
153	google
159	google
165	google
212	google
221	google
223	google
229	google
280	google
310	google
181	search
188	search
196	search
204	search
211	search

Four unused variables
63	initMap
187	searchStyle
195	searchParty
203	searchHotels


### Browser Compatibility



## Deployment

The site is deployed live via GitHub Pages, directly from the master branch, and can be viewed [here](https://stephenjblair.github.io/ucd-project/).

## Credits
### Content
* [FlatIcon](https://www.flaticon.com/free-icon/giraffe_220113) - For use of the giraffe icon.
* [Google Maps API](https://developers.google.com/maps/documentation/javascript/tutorial) - For map and location features.
* [Google Places API](https://developers.google.com/places/web-service/intro) - For points of interest, markers and list results.
