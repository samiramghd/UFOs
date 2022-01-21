# UFOs

UFO Sighting with JavaScript and Bootstrap

### Overview of Project: Explain the purpose of this analysis.

We created UFO Sightings webpage to diaplay a dynamic table which has a Datetime filter section. user can filter the table by adding a date, click on the button and get the results. we’d like to provide a more in-depth analysis of UFO sightings by allowing users to filter for multiple criteria at the same time. In addition to the date, we’ll add table filters for the city, state, country, and shape. 

### Results: Describe how someone might use the new webpage.

Using JavaScript and HTML, we’ll modify the code in the index.html file to create more table filters. so we need to:

- Create four more list elements: city, state, country, and shape in the index.html file.
- Add **updateFilters()** in app.js to save the element, value, and id of the filter that was changed.
- Add **filterTable()** in app.js to loop through the dataset and keep only the results that match the search criteria.
- The webpage should be updated with the search criteria after pressing "Enter".

After completing the webpage, we'd like to show how we can use the filter section. By typing in the suggested placeholder elements as the filters, and "Enter" it will update the results inthe table which we'll go through step by step here.
In the Enter Date we typed the suggested date and results are shown in the picture below

![This is an image](https://github.com/samiramghd/UFOs/blob/main/static/images/date.PNG)

and then we type the city we want in the placeholder, Enter and we get the results

![This is an image](https://github.com/samiramghd/UFOs/blob/main/static/images/city.PNG)

> we have to make sure not have spaces at the end of the text and it has to be exactly the same we have it in table, otherwise it will return blank which we used this part of the code shown in the picture.

![This is an image](https://github.com/samiramghd/UFOs/blob/main/static/images/city3.PNG)


![This is an image](https://github.com/samiramghd/UFOs/blob/main/static/images/city2.PNG)

then we add state, country and shape we want. the results are shown in the picture below.

![This is an image](https://github.com/samiramghd/UFOs/blob/main/static/images/shape.PNG)

> To reset the filter criteria, click the UFO Sightings at the top left of the website.


![This is an image](https://github.com/samiramghd/UFOs/blob/main/static/images/ufo.PNG)


### Summary: In a summary statement, describe one drawback of this new design and two recommendations for further development.

#### Drawback: 

The user must know how to search the specific dates and how to type cities, countries and shapes. The user must make sure there is no space after or not to miss space in between if there is any. 

#### Recommendations:

- I think it's a good idea to add some functions to do auto correction in placeholders and removing spaces before and after the words

- We need to be more clear on the options we can type in the placeholders or maybe using a select box. for example we can add the range of the dates we have in the table, aas a suggested placeholder Date.
