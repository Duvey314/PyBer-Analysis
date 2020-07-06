# PyBer-Analysis
---
### Summary
    
This project is meant to be a primer for using the matplotlib funtions for graphing data. Graphing data can help to understand trends in data or compare different data sets. In this analysis we used data from a ride hailing company, PyBer, and grouped the data first by city type and then by date and city type. We used pandas groupby funtion to seperate the data by city type and the resample function to sort the data by week. In the summary table below we can see that even though there were fewer riders and drivers, the average fare is higher than in the urban or suburban environement. We can also see that for urban cities, there are many more drivers than fares. This pushed down the average fare per driver.

![Summary Dataframe](https://github.com/Duvey314/PyBer-Analysis/blob/master/Analysis/Fig9.PNG)

![Total Fare by City Type](https://github.com/Duvey314/PyBer-Analysis/blob/master/Analysis/Fig8.png)

In the graph above we can see that the the overall revenue for each type of city stays fairly constant but there are a few weeks that perform better than the average. We can also that the urban market brings in nearly four times what the rural market bring in weekly. 

### Challenges

The challenges faced were the same challenges faced when using any sort of new language or library. There is always a learning curve of how certain functions work. In particular I had difficulties with analyzing and sorting data by the date. To overcome this I started by looking at code that dealt with a similar problem to mine. Then I looked at the documentation for the the functions they used to understand what exatly the function was doing. Then I would use that on my code and start with the simplest version and slowly add on the features I needed.

### Further Analysis
  
The most interesting piece of the data to me is the number of drivers compared to the number of fares. In the urban market for example, there are more drivers than there are fares. This is a possible over saturation of the market and few drivers could be used to provide the same amount of service. On the other hand, the rural market is the most profit for each drive so expanding the drivers available could help bring up the revenue from that sector. It would be worth gathering data on how adding or taking away drivers in each market changes the number of fares. Gathering more data for this would mean surveys of current cutomers to make sure that they are not being turned away because they didnt get a driver fast enough or that they are happy with the quality of the drivers they are recieving. Capping or increasing the number of drivers in a market would also illuminate whether or not a market was saturated. Graphing the revenue and the fare per drivers would be able to show market saturation by looking at whether the data plateaus or increase with more driver. These data sets and analysis would help find the optimal number of drivers for each market to ensure that drivers and users needs were met.
