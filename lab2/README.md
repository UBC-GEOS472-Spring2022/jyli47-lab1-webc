# Welcome to Jingyuan's Lab2 Interactive Mapping
# US States Household Composition and Explorationwells
[Link to map: https://ubc-geos472-spring2022.github.io/jyli47-lab1-webc/lab2](https://editor.p5js.org/jli47/full/y6MXzHRHB)
![US House Holder Example and Explorationwell](https://user-images.githubusercontent.com/97953213/159106220-53bc319e-e5c3-4b4e-a545-cf0ce7f91176.png)

In lab2, my topic is about the composition of household in US by States. In the meantime, show the exploration well along east coast Canada. The purpose of interactive mapping could be highlight the states over mouse moving or display the related total household composition data in the information window.

The method we can use chose vector data base map for the state boundary dataset and thematic data by track, however, I only got one states’ household composition data, so I used mapbox styling method to visualize the state to red color, add a new layer using the exploration well vector point data. Chose the necessary components from open street map and changed corlor for the states vaualization on the map. If I could find the whole states houselhold composition data, I could use ArcMap to classify the data by states name to demonstrate the percentage or number of the total household composition, and then convert the shpfile to geojson and export it.  Next, we can use this geojson file with mapbox GL J, generated the interactive map from mapbox, that would be more insightful 

 Using Mapbox Studio created new style and changed it to be able to style up some of my own data within an insightful and relevant visual context. I produced this context through choosing and thoughtfully altering an existing map style. I chose the data is showing the total household composition number in Georgia of Atlanta US state and the explorationwells along east coast Atlantic Ocean.
 
To show the result on the map, we need to code for making html file, load the vector data to the internet, and operate and interactive with users., the number of total hosehold composition will be changed in the information window when mouse move over the states. (In this lab, only Georgia State which is red color works because I only got this state data.)

Finally, joined context of the two layers in the style, shared the style and generated the URL, turned it to the GitHub repositories.  Turned it on the Github and submitted it. 


Data Source:
ArcGIS Hub's open data
Household Composition (by State of Georgia) 2019
Georgia Association of Regional Commissions | opendata@arc
"This dataset was developed by the Research &amp; Analytics Group at the Atlanta Regional Commission using data from the U.S. Census Bureau.For a deep dive into the data model including..."
