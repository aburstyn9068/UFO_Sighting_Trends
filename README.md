This repoisitory contains a project uncovering patterns of UFO sightings in the USA. The team consisted of Adam Burstyn, Sabrina Karam, Francis Marquez, and Angel Milla.

We examined the relationship between household income, drug rates, location, weather and number of sightings of sightings seen. Data was found via various sources cited at the bottom of this document. Jupyter notebook was used to analyze data.

We used an intial data set of ufo sigtings (1) to get general trends based on location (countries, and us states) and season. We found that the US, particularly California, Washington, Florida, New York, and Texas had the highest number of sightings. Additonally summer time had the highest number of sightings. Graphs of the state and season sightings data can be seen below.

![State Sightings](/Images/Sights_State.png)
![Season Sightings](/Images/Sights_Season.png)

We then used the ufo sighting data and compared it to median household incomes at the state level (2). We did not find a strong correlation between ufo sightings and household income as can be seen in the graph below.
![Income vs. Sightings](/Income_Graphs/income_ufo_1996.png)

Next we compared the ufo sighitng data to the weather at the time of sighting (3). We looked at temperature, humidity, cloud cover, and visiblity. 
We found that most ufo sightings occured at 70 degreed F. The range of temperatures within 1 standard deviation of the mean was 37.45 F and 73.46 F.
There was a positive correlation between humidity and ufo sightings.
Ufo sightings were found to be highest during high visibility and 0 cloud cover.

Lastly, we explored drug abuse arrests and ufo sightings (4). We found a positive correleation between ufo sightings and drug abuse arrests.

The presentation slides can be found here:
https://docs.google.com/presentation/d/1zpH9F5Sa0yrnEMJMARCfKpY0vb8LWrP9i0empp1TOdw/edit#slide=id.gcabb73d2ee_0_358

1. https://www.kaggle.com/NUFORC/ufo-sightings
2. https://data.world/garyhoov/household-income-by-state
3. https://weatherstack.com/
4. https://ucr.fbi.gov/crime-in-the-u.s
