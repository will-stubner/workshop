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


JORDAN Country Report

Jordan is a medium income country located in the Middle East. Originating after the Arab Revolt during the first World War, the first Emirate of Transjordan comprised what is today modern day Jordan and most of the West Bank Palistinean territories. The country lacks the oil resources of many of its neighbors, so its standard of living is below that of many other Arab countries. Jordan also is one of the largest centers for refugee populations in the world, with Palestinean communities dating from the 1940's and 1960's and more recently Syrian and Iraqi refugees. These refugees have for the most part intergrated well into Jordanian society, but areas with large concentrations of refugees tend to be much poorer and have much lower access to public services, including transportation and healthcare facilities. Jordan also suffers from a ruarl urban divide, with urban centers often being much more wealthy than smaller settlements and ruarl populations, many of whom are Bedouin, a distinct ethnic and cultural group from the more urbanized Arab population.

![](https://github.com/will-stubner/workshop/blob/master/AMMAN_POP_zoom.png)	
This plot shows the Governates and Districts of Jordan. I used the Jordanian national colors in the plot, with the colors green, red and
black being associated with the country and Arabs more broadly. These colors are the flag of the Arab Revolt flag, so many Arab countries have some or all of these colors. One interesting thing about Jordan is that the red on the Arab flag is actually associated historically with the Hashemite family, who are the current monarchs of Jordan and claim direct matrilineal descendence from the Prophet Muhammad. The current King, Abduallah the Second, is a 42nd generation descendant.

![](https://github.com/will-stubner/workshop/blob/master/jor_populationheat.pdf)

This map depicts the population distribution of Jordan, and a few things are immediately evident. First of all is the large concentration of people in the North of the country in the capital of Amman as well as the cities of Irbid and Zarqa. Roghly 3/4 of Jordan's population lives in the northern parts of the countires, with Aqaba in the south being the only major city not located here. This has historically been the most settled area of the country because the vast majority of the other parts of the country, including the vast Governate of Ma'an, where Petra is located, are mostly heavily desert.

![](https://github.com/will-stubner/workshop/blob/master/bargraph.pdf)
This one was not too hard to make. But it was way harder to combine the plots later.
![](https://github.com/will-stubner/workshop/blob/master/plot_doesnt_work.pdf)
I do not know why this is not working but for some reason everthing is working except for the colors on my bar graph where not working. I do not know why but I tried to get it done by adding some parentheses to the thing.
Response to Stevens
(https://github.com/will-stubner/workshop/blob/master/Stevens)




## PROJECT TWO
Response to Nieves

Random Forests work by aggregating multiple points of data for an individual grid cell, also known as trees, to create an accurate estimate of the population density of a certain area on a map. It relies on using multiple different variables to distribute populations. Essentially how it works is that it starts from the national census that low or middle income countries take. The computer “learns” based on accurate estimates how much a certain factor, including census population estimates, land cover, topography and importantly access to transportation networks like roads and railways, as well as the placement of public services such as health facilities and administrative offices. By analyzing a microcensus, which would survey the population distribution in a certain small area of a country with a high degree of accuracy, the machine can extrapolate with a reasonable degree of certainty the population density of other areas of the country based on the characteristics of the areas surveyed in the microsurvey. Dasymetric population allocation is where the distribution of the population is included, not just the value. So if you had a county map of the United States with population distributions with red being the highest and yellow the lowest, urban counties would be red and rural ones would be yellow. However, on a dasymetric map you might see that some urban counties have sparsely populated areas near airports for instance, with much of the population concentrated in an urban core. Rural counties would be similar, with maybe some suburbs close to a major city or the county seat being a population dense area, but vast parts of the county almost uninhabited. The most important predictor of population density in the random forest model used in this paper was actually land cover, with urban areas obviously being much more dense than vegetated surfaces. As such, this variable is one of the more important “trees” in the forest.


First we have the Model. As you can see the model does a fairly accuarte job at predicting population values. The large positive residulas are likely where refugee camps are hosted.
![](https://github.com/will-stubner/workshop/blob/master/pop_model.PNG)

Next we have the population differences in the enitre country. Again, the refugee camps stand out near Irbid and Amman, where low electrification leads to lower predicted values.
![](https://github.com/will-stubner/workshop/blob/master/pop_differences.PNG)	
Finally, the Amman District includes the large Ba'qaa refugee camp in the north, which reports a signfigant undercount.
![](https://github.com/will-stubner/workshop/blob/master/AMMAN_POP_zoom.png)	





Al-Balqa Urban Areas
Al-Balqa is a very sparesely populated area near the city of Salt in the Balqa governate. I suspect that much of the population simply commutes to Salt for work most days, as is common in Jordan
![](https://github.com/will-stubner/workshop/blob/master/balqa_defacto.PNG)	



In the road network, you can see the Royal Highway in the southern edge of the province, which runs north to south across the country
![](https://github.com/will-stubner/workshop/blob/master/roads.PNG)	
