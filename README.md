# Excel Birding Dashboard

#### [Excel Dashboard](https://github.com/MarkMinia/Project4/blob/main/Dashboard/Birding%20Dashboard.xlsx)

##### Before jumping into Tableau, I experiemented with Excel because of how widely used the program, whether that's in the workplace, school, or at home.

##### Project purpose: This dashboard is more of an informative one. It doesn’t track birds exactly through GPS, but rather gives general sighting locations as determined by field naturalists. So, this does not need to be in real time. It has more of an advertising component to it. If more people take interest in this dashboard for bird information, they might view the state park more favorably and either donate or visit more often. So, make sure this dashboard inspires people’s love for birds and is attractive and fun.

##### User/audience: Tourists/birders visiting a state park’s website.

##### Core elements included in dashbaord:
- ##### Heatmap of Vermont using zip codes
- ##### Horizontal bar graph displaying total sightings by zip code and by bird species
- ##### Dropdown with a brief description of each bird

##### The following birds were used in this dashboard, although the locations were at random for the purpose of creating a heat map:
- ##### Peregrine falcon
- ##### Yellow-bellied sapsucker
- ##### Golden-winged warbler	
- ##### Bobolink
- ##### Eastern towhee	
- ##### Chimney swift
- ##### Scarlet tanager	
- ##### Red-breasted nuthatch
- ##### Wood thrush	
- ##### Blue-winged warbler

##### When creating this dashboard, we weren't given a data set to experiement with, so I decided to created a table using randomly generated numbers. This is so that I could personally practice creating dynamic images using pivot tables rather than present static ones. I decided to go with a more portrait oriented style because I wanted it feel like a mobile application due to birding being a mobile activity; you're traveling from one place to another trying to find these specific birds in the area so you're likely going to be using this dashboard on your phone and not on a laptop or desktop. 

##### The heat map and bar graph involved creating pivot tables, then slicing the data so that it enables me to select the specific values I want and changes the graph according to my selection. Creating the bird drop down with the image and description was more complicated because there were additional steps and functions required. A bit of prepping was involved in a different tab to ensure the names of cells and the way it was arranged would allow the functions to work properly. I needed to use Data Validation, an INDIRECT function, and a VLOOKUP funtion so that the image and description changed altogether when selecting from the drop down. 
