# PyBer_Analysis

## Purpose

  The purpose of this analysis is to visualize PyBer performance between three city types--Rural, Suburban, and Urban. The data was analyzed using Pandas, and Matplotlib in Python. 
![PyBer High Level Summary](https://github.com/n-toy/PyBer_Analysis/blob/master/Analysis/Challenge%20Summary.PNG)
  A high level summary of the PyBer rider data shows that use of PyBer is higher in Urban areas, but with the lowest average fare for ride and driver performance. Rural and Suburban cities show a disproportionate view of PyBer effectiveness with lower number of rides, and higher costs.
![PyBer 2019 Q1 Fares](https://github.com/n-toy/PyBer_Analysis/blob/master/Analysis/Challenge.png)
  Looking at 2019 Q1 performance between the three city types Urban and Suburban cities fares ($USD) are rising, while Rural seems to be stagnant. 

  The challenges faced while putting together this analysis was working with Pandas DateTime format, and visualization formatting. The Datetime issues were related to initializing the Data Frame Date column as an index before setting the format of the column. Through careful backtracking I was able to find that declaring the index too early was causing DateTime calculations to fail. The Visualization formatting proved to be troublesome at first as I wasn't familiar with the input commands for plotting. Matplotlib lets you call individual plot elements line by line, whereas I have more experience with GGPlot2 in R. Through this analysis I uncovered a lot about plotting in Matplotlib.
	
  Based on the available data, there may be opportunity to bolster Rural city performance by encouraging more Drivers to sign up. We see a very large number of Drivers in Urban cities compared to the other two city types that may be a factor. What would be helpful if we had it would be to add average wait time, and average trip length/duration to understand what is happening between the city types. Average fares in Rural and Suburban cities may be driven by longer trips or time to destination. If we had this additional information at the Ride ID level it could be merged, and then added to the summary table. 