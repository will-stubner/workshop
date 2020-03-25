# catalog

William Stubner

## Workshop

1. Line Plot
2. Path of A Salesman

## Project 1

1. ...
[blumenstock reading] (https://github.com/will-stubner/workshop/blob/master/Blumenstock.md)
2. ...
[Lloyd Reading] (https://github.com/will-stubner/workshop/blob/master/Response_to_Lloyd.md)
3. ...
Wardrop Reading (https://github.com/will-stubner/workshop/blob/master/Wardrop_response)




(https://github.com/will-stubner/workshop/blob/master/jordan.pdf)
This plot shows the Governates and Districts of Jordan. I used the Jordanian national colors in the plot, with the colors green, red and
black being associated with the country and Arabs more broadly. I did not have too many problems making this one, other than some early 
problems.

(https://github.com/will-stubner/workshop/blob/master/jor_populationheat.pdf)
This one was pretty difficult to make. I had trouble naming the variables and when I downloaded the inital raster I kept getting the number of gridcells confused with the number of people. I think the population is roughly half of what it is supposed to be, but that's better than the previous number.

(https://github.com/will-stubner/workshop/blob/master/bargraph.pdf)
This one was not too hard to make. But it was way harder to combine the plots later.
(https://github.com/will-stubner/workshop/blob/master/plot_doesnt_work.pdf)
I do not know why this is not working but for some reason everthing is working except for the colors on my bar graph where not working. I do not know why but I tried to get it done by adding some parentheses to the thing.
Response to Stevens
(https://github.com/will-stubner/workshop/blob/master/Stevens)




## PROJECT TWO
Response to Nieves

Random Forests work by aggregating multiple points of data for an individual grid cell, also known as trees, to create an accurate estimate of the population density of a certain area on a map. It relies on using multiple different variables to distribute populations. Essentially how it works is that it starts from the national census that low or middle income countries take. The computer “learns” based on accurate estimates how much a certain factor, including census population estimates, land cover, topography and importantly access to transportation networks like roads and railways, as well as the placement of public services such as health facilities and administrative offices. By analyzing a microcensus, which would survey the population distribution in a certain small area of a country with a high degree of accuracy, the machine can extrapolate with a reasonable degree of certainty the population density of other areas of the country based on the characteristics of the areas surveyed in the microsurvey. Dasymetric population allocation is where the distribution of the population is included, not just the value. So if you had a county map of the United States with population distributions with red being the highest and yellow the lowest, urban counties would be red and rural ones would be yellow. However, on a dasymetric map you might see that some urban counties have sparsely populated areas near airports for instance, with much of the population concentrated in an urban core. Rural counties would be similar, with maybe some suburbs close to a major city or the county seat being a population dense area, but vast parts of the county almost uninhabited. The most important predictor of population density in the random forest model used in this paper was actually land cover, with urban areas obviously being much more dense than vegetated surfaces. As such, this variable is one of the more important “trees” in the forest.
