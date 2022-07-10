# UFOs
## Overview
##### We assisted Dana in creating a website that displays data on UFO sightings with the additional user interactivity feature of filters that will allow users to pinpoint the sighting(s) they wish to learn more about. The data on UFO sightings we used for this project is stored in a JavaScript file, where we then created app.js, index.html, and style.css files to customize our website to our desired result.
## Results
##### Our webpage is easy to use, allowing users to filter by just one category or by a mix-and-match or by all. Below is a walkthrough of how a user could narrow down their initial search by date by adding more information to the filters. 
![UFOs_homepage.PNG](https://github.com/carinaediaz/UFOs/blob/main/Static/Images/UFOs_homepage.PNG)
##### When first navigating to our webpage, you will be greeted with a similar result to above. The table contains all of the data available within the data.js file that stores our UFO sightings information and the filters have prompted text to indicate to the user that they can enter information in the search bars. 
![UFOs_date_search.PNG](https://github.com/carinaediaz/UFOs/blob/main/Static/Images/UFOs_date_search.PNG)
##### In the example above, the user first filters the table by date. We see that the table results are less than before (the navigation bar on the right of the screen is larger), indicating some sightings have been filtered out. 
![UFOs_state_search.PNG](https://github.com/carinaediaz/UFOs/blob/main/Static/Images/UFOs_state_search.PNG)
##### Here the user has decided to further filter the sightings results by entering a state. Once again, we see that the table results are less than before. 
![UFOs_city_search.PNG](https://github.com/carinaediaz/UFOs/blob/main/Static/Images/UFOs_city_search.PNG)
##### The user has decided to add a city to their filter searches, drastically reducing our search results. We are now able to see all of our results on one page. 
![UFOs_country_search.PNG](https://github.com/carinaediaz/UFOs/blob/main/Static/Images/UFOs_country_search.PNG)
##### If our user decided that they wanted to use all of the filters, they could add a country to their search. In this case, our search results did not change. 
![UFOs_shape_search.PNG](https://github.com/carinaediaz/UFOs/blob/main/Static/Images/UFOs_shape_search.PNG)
##### Lastly, our user entered a shape criteria. Our final results are two sightings.  
## Summary
##### Our first version of our website only contained a filter for the sighting date. We improved our interactivity features by adding filters for city, state, country, and shape. Our final version allows users to further define their search to meet their interests, but there are additional features that could be added to improve the user's experience. 
##### While our search bars contained prompted text that indicates to the user what kind of text that they could enter, it does not tell them that the searches are case-sensitive. A user could attempt to enter "El Cajon" instead of "el cajon" (the format in which the data is stored) and would receive zero results, leaving it easy to assume no sightings have been reported in that city instead of it being a formatting error. Instructions on how text should be formatted or updating our code to accept both lower and upper-case would be beneficial. 
##### Additionally, users may want to search by more than one date, city, state, country or shape at a time. Adding an option to enter multiple criteria to a filter would enhance the user's interactivity with the data.
