# UFOs

Javascript and Bootstrap Practice for Module 11

## Overview

The purpose of this analysis was to use Javascript and HTML to assist our friend Dana in setting up a webpage that will search through a database of UFO sightings.

## Results

Dana's table can be accessed at https://alexsherry21.github.io/UFOs/

### Instructions

In our index.HTML file, we built a filter table that takes user inputs for a sighting's date, reported shape, and location by city, state, and country.  A user can type lowercase into one or many of the input elements, upon which an event listener in our app.js file triggers a loop through the data that filters it to rows that match the inputs.  To get back to the original table the user can either refresh the page or clear the input boxes and hit enter.

### Images

#### Default

![image](https://user-images.githubusercontent.com/100380226/169723858-7f803e82-dd37-4c40-ac77-06c5cc74db7d.png)

#### Filter by state: tx

![image](https://user-images.githubusercontent.com/100380226/169724092-926ca024-be0a-432c-a89b-a26668bfb9a2.png)


#### All filters

![image](https://user-images.githubusercontent.com/100380226/169724059-90aabc87-6cc9-4386-96c0-c66e425567a5.png)

### Summary

One drawback of the current website design is that while the filters can be applied together, they don't allow for ranges or multiple selections within the filters, such as a span of a few months or a tri-state area.  Researchers might want to search through the data using multiple selections in a filter to group occurances together.  One recommendation for further development would be to relax the input elements' case sensitivity.  While users would proabably figure it out anyway, allowing people to enter "new york", "New York", "NEW YORK", "new_york" etc and get the same results would improve ease-of-use somehwat.  Additionally, formatting the site for a couple more screen sizes would make it look more professional.  Overly stretched-out or compressed images can be an eyesore for readers.  One last idea would be providing links to news sources or to where one could report a UFO sighting, as both of these could boost engagement.
