# Welcome to Jingyuan's Lab1 Web Cartography
[Link to map: https://ubc-geos472-spring2022.github.io/jyli47-lab1-webc/](https://api.mapbox.com/styles/v1/jli47/cl02skpqv00fo15n7t28il3ak.html?title=view&access_token=pk.eyJ1IjoiamxpNDciLCJhIjoiY2wwMjc5dmRqMHE5eDNvcnlwd29zY3EyayJ9.zcqlSyi6nKyEO9JU36hy1w&zoomwheel=true&fresh=true#10.58/49.2055/-122.8223)

In this lab, I chose vector data base map for the country dataset.  Using Mapbox Studio created new style and changed it to be able to style up some of my own data within an insightful and relevant visual context. I produced this context through choosing and thoughtfully altering an existing map style. I chose the data is showing the place that the students are interested in, which is varied Vancouver we did the activity in early class.

To show those places in the map, I needed to effective and value the thoughtfulness of the styling over the over elaborateness of it. It made city patterns clearly. First of all, created the new style and changed the layer as below,
1. Water including ocean, rivers, lakes and stream (color to blue)
2. Road network surface
- Road major-link (color to orange)
- Road-primary (color to yellow) 
- Road secondary-tertiary (color to purple)
- Road-street (color to purple)
- Road motorway-trunk-case (color to dark grey)
3. Land, water, &sky water
- landuse ( color to soil tone)
- National-park (color to green)
- Land.  
4. Transit built
- /aeroway-line ( color to grey, make line label visible)

Then, I added new layer from the varied Vancouver geojson file

- The student’s interested points, red circle points demonstrated in the map.

Finally, joined context of the two layers in the style, shared the style and generated the URL, turned it to the GitHub repositories. It could interactive with user using the scale button and see the place details. In advanced map design, it could add some functions to add or delete the place circle point for approving the project.
