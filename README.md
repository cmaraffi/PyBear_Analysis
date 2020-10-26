# PyBear_Analysis
Matplotlib and Pandas

## Overview of the Project:
A detailed analysis for V. Isualize's ride-sharing data. They want to see various views on the city types (Urban, Rural, and Suburban) using various aspects of the data. 

1. Merge separate data frames for city data and ride data into a single dataset
2. Get the types by city.
3. Get the rides by city.
4. Get the total drivers by each city type and total fares
5. Get the averages for both rides and drivers each city type.
6. Create a dataframe of all the newly mapped data.

### Resources
- Data Source: city_data.csv , ride_data.csv
- Software: Pandas and Jupyter Notebook

### Summary
The analysis of the city types show that:
- Urban fares are the most data over the four month timeframe displayed.
- Of total overall 1,375 rides were:
    - Rural : 125
    - Suburban : 625
    - Urban : 1625
- The city type results were:
    - Rural the average fare per driver was the highest at $55.49. This seems logical because its ususally the most distance traveled. 
    - Suburban fares averaged about $31 per ride and are 3.4x more frequent than rural ones.
    - Urban fares were the cheapest fare mostly due to the fact travel is such a short distance.

### Challenge Overivew
- Learning both Matplotlib and more in-depth Pandas dataframe was an enjoyable exercise. The keywords and ability to manipulate data efficiently was my favotire part of the exercise. 

- Setting up the csv file. I did update the data through text to columns options and then saved the file as a csv file. It made it easier for read and decipher when updating the dataframe. Getting all of the individual pieces were relatively straightfoward both because the module was clear as well as getting some freedom to build upon what we previously learned with Pandas. Using the groupby() method is something that seems very versatile and I will be exploring it more in depth. Getting the individual fares, rides, and drivers were also interesting. Then changing the index to date and manipulating the fares to get to a pivot table was definitely a new endeavor but also something that had very logical steps. I played around with resampling a couple times just to see the different outcomes. Then graphing the data I thought you would have to do some more in details for getting all three lines on the chart. That definitely required outside research as well as the loc method. It was a lot simpler than I originally thought. It was a really nice output to complete the graph and close out the project for V. Isualize. 

- Overall, the module itself was very informative and valuable and can definitely see myself using this in my professional life going forward. 

### Challenge Summary

- V. Isualize's ride-sharing data seems to have consistent ride fares no matter the destination. While, urban rides are the least expensive, at about 50% of the fares  being under $25 dollars, they are the most lucrative. Also over this specific four-month time frame in 2019, the standard deviation for rural vs urban is 14.7 vs 12. As far as the rural and urban fares, which do have less frequency, there might be an opportunity there to review the current fare price vs the cost to the drivers. This data presented in the final summary will help make some important business decisions for V. Isualize for PyBer. 

