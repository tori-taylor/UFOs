# UFOs
## Overview of Project
The purpose of this project was to take a large data set of UFO sightings and turn it into a user friendly website.

## Results
When a person first comes to the site they can easily see all recordings in a table, image is below.

![table](https://github.com/tori-taylor/UFOs/blob/main/static/images/table.PNG)

If they would like to look at data for a specfic city, state, country, date, or shape, they need to type in what they are looking for in the filter boxes below. The table will automatically give results for what they have selected to filter on.

![filters](https://github.com/tori-taylor/UFOs/blob/main/static/images/filters.PNG)

## Summary
One drawback of these filters is that you have to type in the state/city exactly as it is spelled in the table. This could cause some confusion. If possible I would suggest a drop box for the filter so that nothing can be spelled wrong. Second suggestion is that when you filter on something with no sightings there should be automated message like "no sightings". For example if you are searching for New Zealand sightings and type "nz" the table just comes up blank. A person may think there is an error instead of being sure there were no sightings.

When I had issues with the code most specifically the "changedElement", I referenced https://github.com/Baylex/UFOs/blob/main/static/js/app.js
