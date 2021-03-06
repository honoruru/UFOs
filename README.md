# UFOs Analysis


## Project Overview

The purpose of this project is to develop a website allowing users to filter through a list of UFO sightings on multiple criteria at the same time.  The user can filter for the date, city, state, country, and/or shape of provided list of sightings.

## Results

Describe to Dana how someone might use the new webpage by walking her through the process of using the search criteria. Use images of your webpage during the filtering process to support your explanation.

The search tool can be used following the instructions below:

1.	Hit “UFO Sightings”

 <img src="https://github.com/honoruru/UFOs/blob/main/Challenge%20Images/top%20image2.png" width="200" height="180"/>

<p align="center">
 
</p>

2.	Enter values for one or more filters 

 <img src="https://github.com/honoruru/UFOs/blob/main/Challenge%20Images/Menu%20image2.png" width="200" height="600"/>

3.	Example of search on 1/1/20 with default values for all other fields.
 
 <img src="https://github.com/honoruru/UFOs/blob/main/Challenge%20Images/page%20image.PNG" width="600" height="600"/>


4.	No entries will return the entire list.
5.	Filters are AND, not OR, i.e., items returned on list must satisfy all criteria input.
6.	To clear field value, entry must be deleted.
7.	Alternatively, hit “UFO Sightings” to reset values (i.e., quick reset) to defaults and return to top of page.

## Summary

### Drawback 

There are a number of drawbacks to the current construction of the tool. One is that the input fields layout are prone to lead to futile searches, some of which could be due simply to misspelling or formatting (e.g., "CA" does not satisfy "ca" for state input).


### Recommendations for Improvement
Several recommendations are submitted for consideration to improve the experience and enjoyment when using the tool.
1.	Clean Duration data which currently includes misspellings and inconsistent formats (e.g., 1 minute vs. one minute). 
2.	Create a “Clear Fields” button placed near input fields.
3.	Have pull-downs for city, state, country, and shape. This will limit searches to values actually in the list. 
4.	Change placeholders to give clues to user. This change has already been made (to illustrate) so that the placeholders match the first item on the default list.  This provides user a visual cue as placeholder values match something user sees in default list. 
5.	Add filter for Duration using "less than" and "greater than" for time duration in minutes.  
6.	Filters are AND. Create an option to change to OR.

