# UFOs

## Overview of Project
This project was to design a webpage that would search a javascript webpage and deliver results on all UFO experiences. This list of data was also designed to be filtered by user input.
## Results
The webpage contains the ability to filter results by Date, City, State, Country, or Shape of UFO sighting and produces details on comments.
#### Main Filters
![](https://github.com/NortonAAA/UFOs/blob/main/images/filters.png)

#### Examples of Searches
Search by Date (ex.1/13/2010) ![](https://github.com/NortonAAA/UFOs/blob/main/images/filter_by_date.png)

Search by State (ex.Oregon) ![](https://github.com/NortonAAA/UFOs/blob/main/images/filter_by_state.png)
## Summary
While this new design allows for more filters its is designed currently to be limited on just those fields, if you know the inputs to those fields, and acts as an AND function. This narrows results if more than one filter is used.

Two recommendations to fix this would be:
1) Update the code to return the results of each filter to the table that were true. For example, all results from the state of california or the results for the date. 
2) Make the user inputs less prone to zero results if inaccurate information is chosen. This would mean updating the code to change input to ".lowercase" in the code to convert information to the data's structure.