# Climate_Change_and_Precipitation_Patterns

Global Warming is becoming an increasingly important issue due to the effects it's having on humans and the environment all over the world. That is why it has been the center of attention in large humanitarian and goverment institutions.

We have decided to base our final project on issues of global warming and its effects on the environment. The one particular side effect we are going to be looking at is a change in precipitation patterns around the world. We have gathered data from Our World in Data and NOAA to analyze the patterns of global warming and precipitation throughout the decades.

We believe that we are going to see subtle changes in some parts of the world but some more drastic changes in precipitation in some other regions. This is because global warming has caused more dramatic temperatures by giving us colder winters and hotter summers. However, places where temperature is fairly constant throughout the year, we believe might not be affected by global warming as much. These regions tend to lie closer to the equator. Now let's see if our hypothesis is correct.

## Results
The PDF result can be accessed here: https://aparyavi.github.io/Climate_Change_and_Precipitation_Patterns/

### Regional Temperature Increase Analysis
<img width="660" alt="Screenshot 2023-11-14 at 6 40 26 PM" src="https://github.com/aparyavi/Climate_Change_and_Precipitation_Patterns/assets/62215723/91effcf5-de3a-4bce-b792-1f9ae9cb7992">
<img width="634" alt="Screenshot 2023-11-14 at 6 41 14 PM" src="https://github.com/aparyavi/Climate_Change_and_Precipitation_Patterns/assets/62215723/71ac59ba-2250-4a1f-a7ef-19b81f22e4af">

These graphs give us a very good insight into what is happening with the temperature around the world. It is obvious that some regions of the world have a more dramatic increase in temperature as opposed to some others. To better understand the temperature increase difference, we can also see the exact average increase in temperature per year in each region before the graphs.
For example, North America has the absolute highest increase in temperature and Asia is next. However, places like the Caribbean Islands or Atlantic MDR have some of the least increasing temperatures around the world (but they're still increasing). We can definitely see a correlation in the region since they both are very close if not on the equator line. And North America is over the equator line that is why it has the most extreme effect on there. Based on the article Which parts of the planet are warming the fastest, and why? "The earth's largest land masses and its north and south poles are warming the fastest, mainly because of differences in how these areas reflect energy from the sun" (Climate Portal).

### Regional Temperature Increase Analysis with Barplot
<img width="875" alt="Screenshot 2023-11-14 at 6 43 01 PM" src="https://github.com/aparyavi/Climate_Change_and_Precipitation_Patterns/assets/62215723/11859b67-a3ec-44e9-8293-fe8245bff47a">

Looking at the barplot, we can easily see the differences in temperature change in different regions of the world. The red dotted line is the global average. As we can analyse in the previous section North America and Asia have the two highest increases in temperature in the entire world. This shows how dramatically temperatures are changing in some parts of the world.

Top two:
North America - 0.02233
Asia - 0.01826
Bottom two:
East N Pacific - 0.00704
Caribbean Islands - 0.00877

### Top 15 States Plot
We can use many different types of plots for this section. But barplots are the best option for our purpose. We want to get a visual on the top increasing states in precipitation and compare it with the US average.

Now we are going to do a barplot of the top 15 states to better visualize the different states and their increase in precipitation. This might help us and anyone reading this tutorial to better understand the change in precipitation in different regions of the country.

We run a red dotted line indicating the US average.

<img width="748" alt="Screenshot 2023-11-14 at 6 45 55 PM" src="https://github.com/aparyavi/Climate_Change_and_Precipitation_Patterns/assets/62215723/f050de5f-ccb0-446a-9700-c4631f503c59">

In this barplot we can see that these states have more than twice the US avergae precipitation increase. That is a staggering amount. Now, we're going to see if there is any pattern in the regions in these top 15 states.

We can see that the top 15 states with the highest increase in percipitation are mostly from North Eastern Part of the US. Rhode Island, Vermont, New Hampshire and Massachusetts are just the top 4 states and they are all in the most North East part of the US. There are also a few states more towards the Central US, but still East such as Michigan and Mississippi. However in the top 15, we do not have a single state from the West. And they are mostly states towards the North. We can see from this that precipitation is being effected more significantly in the North and places where precipitation was already high.

### Bottom 15 States Plot
As described above, we can use many different types of plots for this section. But barplots are the best option for our purpose. We want to get a visual on the bottome decreasing/increasing states in precipitation and compare it with the US average.

Now we are going to do a barplot of the bottom 15 states to better visualize the different states and they're decrease/increase in precipitation.

We run a red dotted line indicating the US average.

<img width="767" alt="Screenshot 2023-11-14 at 6 47 07 PM" src="https://github.com/aparyavi/Climate_Change_and_Precipitation_Patterns/assets/62215723/e95b5169-622b-4ba5-a388-708b00115939">

In contrast to the top 15 states, we can see that all of the states that either have a decrease in precipitation or have a very slight increase in precipitation are Central and Western states. We can see that Arizona and California have had a decrease in average precipitation. This can be because, most of these states are drier and thus the climate change has not effected them as much.

#### Precipitation Conclusion
We can conclude that overall, the US annual precipitation is increasing. Even in the bottom 15 states, only two of them had a decreasing trend in their precipitation and the rest were all increasing but just at a lower rate.

There is also a strong link between the region in the country and the amount that precipitation is increasing. We might be able to find a correlation between the region and the temperature change and that is what we are going to find out in the next section.

### Top Increasing Precipitation vs Temperature
Here we are going to plot the top states that have shown highest increase in precipitation in the US and we are going to plot them against temperature. By doing this we can see if there is any trend.

If you want to learn more about subplots click [Subplots](https://www.tutorialspoint.com/how-to-make-two-plots-side-by-side-using-python).

<img width="908" alt="Screenshot 2023-11-14 at 6 49 07 PM" src="https://github.com/aparyavi/Climate_Change_and_Precipitation_Patterns/assets/62215723/9371fabe-6538-4aa1-b86b-46aedc69a069">
<img width="864" alt="Screenshot 2023-11-14 at 6 49 28 PM" src="https://github.com/aparyavi/Climate_Change_and_Precipitation_Patterns/assets/62215723/d1d3ed08-1894-440b-a197-b985dc492b11">

We can see that some of the states have a very good correlation between their increase in precipitation and the temperature. Michigan, New York, Illinois and Indiana show a definite increase as temperature increases. However, states such as Connecticut, Massachusetts and New Hamshire do not show much correlation and their plots are very scattered meaning that even at lower temperatures we have gotten high precipitation readings.

One thing that, however, they all have in common is that all of their regression lines are sloped upwards. Meaning that they all have at least a slight increase in precipitation when temperature increases.

### Most Decrease/Least Increase Precipitation vs Temperature
Here we are going to plot the bottom states that have shown the least increase or even a decrease in precipitation in the US and we are going to plot them agains temperature. By doing this we can see if there is any trend.

<img width="811" alt="Screenshot 2023-11-14 at 6 50 28 PM" src="https://github.com/aparyavi/Climate_Change_and_Precipitation_Patterns/assets/62215723/96ab1b55-f018-4afa-9b01-7777a187573b">
<img width="770" alt="Screenshot 2023-11-14 at 6 50 49 PM" src="https://github.com/aparyavi/Climate_Change_and_Precipitation_Patterns/assets/62215723/8317f807-cc5c-46f1-8a16-0b16163cb3b2">

In this part we have gotten some very interesting data. We have a very flat slope for most of the states, meaning that as temperature increases, the precipitation pretty much stays the same. In some states we are even getting a negative slope. However, this makes sene, since these states we had already established that they didn't have much change in precipitation and two of them had a decrease in precipitation.

Since, these states were mostly in the wester/central parts of the US and also these are the more dry states in the US. We can conclude that the temperature is not effecting drier regions of the country as much as it is effecting states that already had high precipitations.

## Conclusion
In this tutorial, we have gone over many different aspects of climate change and precipitation. We have seen that climate change is not affecting every region of the world at the same rate. The degree of change depends on so many variables. The variables that we were able to see were that, at regions closer to the equator, we had less change in the temperature. In contrast, we had the most change in North America which is above the equator.

We then analyzed the precipitation patterns in the United States. We saw that precipitation was generally increasing in the US. We then analyzed the states individually and found out that the most drastic changes in temperature are happening in the North Eastern parts of the US. In contrast, the least affected states are states on the West Coast or in the Central US. This shows again that as the temperatures rise, the effects are not going to be evenly distributed and there are biases based on the regions. The correlation between the increase in Temperature and Precipitation is more evident in states that have higher overall precipitation.

In this tutorial, we have used a series of plots and regression lines. Barplot and scatter plots were the two different types of plots we used. We also used regression lines and average lines to make better sense of our data. For more resources and tutorials on what we used, we have included some links in the "References" section.

References:

Precipitation Data from the United States Environmental Protection Agency - https://www.epa.gov/climate-indicators/climate-change-indicators-us-and-global-precipitation
<br />
Annual Global Temperature Averages - https://datahub.io/core/global-temp#data
<br />
National Centers for Environmental Information, National Oceanic and Atmospheric Administration (NOAA) - https://www.ncdc.noaa.gov/cag/global/time-series/
<br />
Scatter Plots - https://matplotlib.org/3.5.0/api/_as_gen/matplotlib.pyplot.scatter.html
<br />
Linear Regression - https://realpython.com/linear-regression-in-python/
<br />
Which parts of the planet are warming the fastest, and why? - https://climate.mit.edu/ask-mit/which-parts-planet-are-warming-fastest-and-why#:~:text=The%20earth's%20largest%20land%20masses,reflect%20energy%20from%20the%20sun.&text=For%20more%20than%20a%20century,labs%2C%20ships%2C%20and%20satellites.
<br />
Barplot - https://matplotlib.org/3.5.0/api/_as_gen/matplotlib.pyplot.bar.html
<br />
Dataframes and Arrays - https://www.geeksforgeeks.org/create-a-dataframe-from-a-numpy-array-and-specify-the-index-column-and-column-headers/
<br />
Subplots - https://www.tutorialspoint.com/how-to-make-two-plots-side-by-side-using-python
