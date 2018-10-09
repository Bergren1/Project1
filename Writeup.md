## GES 486 Project 1

**Objectives**

This project was aimed at creating geospatial analysis of the relationship between race and access to public transportation within the city

While it is well known that Baltimore has poorly funded public transportation systems, it may be less obvious how this infrastructure is disproportionately accessible based on factors such as race.

![](https://user-images.githubusercontent.com/42807663/46647331-6adc0000-cb5d-11e8-8059-456c2a920288.jpg)



As seen in the map above, Baltimore railways and Circulator busses are highlighted in Yellow and blue respectively, contrasting heavily against the neighborhoods with the highest white populations (highlighted in Black and Dark purple).

This highlights the intense disparity in access to public transportation based on location and Race.

**Methods and data**

The main pieces of data that were used in this project were 2010 Census blocks, Charm City Routes, and Railways, taken from https://data.baltimorecity.gov/
and the Baltimore City Polygon (Used Only for the drop shadow), taken from http://gis-baltimore.opendata.arcgis.com/.

To manipulate this data, I used a Spatialite database (*pictured bellow*) to organize the data, as well as a series of simple SQL queries (*also pictured bellow*) to determine what percentage of each transit system serviced majority white populations. From here, it was mererely a matter of stylizing the map in such a way that adequately represented the data, but did so in an attractive, easy to read manner.

![](https://user-images.githubusercontent.com/42807663/46647339-78918580-cb5d-11e8-87cf-c9d7dd71b3c8.PNG) ![](https://user-images.githubusercontent.com/42807663/46647343-7cbda300-cb5d-11e8-8fe0-6c3d1af3a901.PNG)

Finally, I chose make a 3D model of my map in order to display the contours of Baltimore (Pictured Bellow), which is especially important when evaluating the severity of transit disparity. Steeper parts of the city may require greater transit density.
![](https://user-images.githubusercontent.com/42807663/46647396-c0b0a800-cb5d-11e8-85a7-26ab5e27c7ab.png)![](https://user-images.githubusercontent.com/42807663/46647399-c4442f00-cb5d-11e8-91fc-2376e00bb561.png)
