# UFOs
Build a dynamic table using data stored in JavaScript and then customize the table into an HTML file using Bootstrap to make the page easy to read and user friendly.

## Overview of Project
This project involves creating a webpage by web scraping using javascript. The final webpage provides an in-depth analysis of UFO sightings with a table of the reported sightings. Next to the table, there are multiple filter options to allow users to filter the table for date, city, state, country, and shape. The user can input the criteria for the desired number of filters that they want to find (choosing from the provided filter options). As information is entered into the filters, the table will update with the results matching the user's input.

## Results 
To perform a specific search, the user can navigate to the appropriate filter id; for example, state and enter their state. Once the new state is entered, the table will populate with all UFO sightings recorded in that state. If the user wants to input a date, city, country, or shape description as well this can be done and the table will update accordingly, however not every filter needs new input from the user. See the example of screenshots below showing the html page before any filters are added and after filtering for the country Canada and then again filtering for the state of Texas.

Table without filter:

![UFO table no filter](https://github.com/kmaluccio/UFOs/blob/main/static/images/UFO_table.png)

Table with filter for country:

![UFO table with filter](https://github.com/kmaluccio/UFOs/blob/main/static/images/UFO_filteredTable2.png)

Table with filter for state:

![UFO table with filter](https://github.com/kmaluccio/UFOs/blob/main/static/images/UFO_filteredTable.png)

Note: There are many different filter combinations, so you can filter for date, city, state, country, and shape all at once or individually or any combination of these filters.

## Summary
- One drawback of this webpage is that the filters for the table has to be decided by the user. This could be an issue because the user might enter information (date/city/state/etc) that is not found in the table and they will need to keep searching.
- Another drawback is that there is no requirement for how to enter the data (placeholders do help show how it should be entered, but this could be improved).
- Recommendations for further development of the webpage:
	- One recommendation would be to add drop down boxes for each filter to show the user what options are in the table. This way, when the data is filtered the user knows that the selections they have made to filter will have at least one row of a UFO sighting.
	- Another recommendation would be to have a filter for the year instead of the exact date. The date has to be entered as month/day/year and it might be of interest for users to filter the table for the year only.
	- A final recommendation is to create a summary of the data in the table. For example, in the summary you may find a list of the different shapes or a list of all countries where UFO sightings have happened so that the user would not have to scroll through the table to see all possible shapes or countries where these sightings were recorded.

