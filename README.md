# UFO Sightings

![ufoBanner2](https://user-images.githubusercontent.com/81998045/124376387-c9822a00-dc74-11eb-8e1d-f5520c2fe98a.png)


## Overview of the analysis:
### Scenerio:
Dana is a data journalist who has been given the opportunity to write about her hometown, McMinnville, Oregon, which has gained some fame for UFO sightings a topic she's excited to write about. Dana will be posting her article online and will be creating an HTML webpage where she'll include an interactive table with all UFO sighting data allowing users to search by filtering for multiple criteria at the same time i.e., date, city, state, country, and shape.


## Results: 

Below is the UFO Sighting webpage interface which includes the article "UFO Sightings: Fact or Fancy? Ufologists Weigh In."

<img width="1424" alt="Webpage main" src="https://user-images.githubusercontent.com/81998045/124375206-ffbcab00-dc6e-11eb-984e-583bac89ca4c.png">



Using the interactive filters below, users can search for UFO sightings according to date, city, state, country and shape. For example, the user below searched for UFO sightings on 1/13/2010 and the table displays all UFO sighting on that date with other details. We've provided some default text shown in gray to help users enter correct formatting for each criteria.

<img width="1414" alt="Filter search result" src="https://user-images.githubusercontent.com/81998045/124375229-2c70c280-dc6f-11eb-89c7-5b27d29d893c.png">


Users can also use multiple filters for more specific search results, as the user enters information for each filter, the table of data on the right side is filtered to match the user input criteria. The image below shows the filtered table of a user's search for UFO sightings in the city of "willow" and the state of "ak"

<img width="1423" alt="city_state_filter" src="https://user-images.githubusercontent.com/81998045/124394809-01b65680-dccf-11eb-99a2-cab140ad2c91.png">

## Summary 
- One drawback of this design is that all input for filter criteria is formatted as a string, giving the user the ability to type in their criteria leaves more room for error when considering grammatical errors which would affect search results. 

### Recomendations

  1) The first recommendation would be to add a drop-down menu providing all countries, states, and cities to eliminate user spelling errors. 
  
  2) Another recommendation would be to adjust the order of the filters to date, country, state, city and shape. This order would be ideal because when entering the country, it will automatically eliminate search results from other countries but also states and cities that aren’t in that particular country. Starting the search with "city" can be vague when considering there may be several cities with the same name in several states and countries. 
  
  3) I would also include the filter button which again provides the user with clear, logical next steps showing they have concluded inputting their search filters and creating a clear path to their search results, the idea is to make the webpage as user friendly as possible eliminating user error as much as possible.
