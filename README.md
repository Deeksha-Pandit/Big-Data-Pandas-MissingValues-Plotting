# Big-Data-Pandas-MissingValues-Plotting

### In this problem set, we will be exploring 5 problems:

Exercise 1 and Exercise 2 would give you an insight on using pandas.  
Exercise 3 will focus on cleaning the dataset for missing datapoints.  
Exercise 4 and Exercise 5 would involve generating graphs based on the traffic dataset.

This exercise discovers an extensive dataset on the subject of traffic on German roads provided by the BASt. It holds detailed numbers of cars, trucks and other vehicle groups passing more than 1,500 automatic counting stations. This dataset records for each counting station are provided on an hourly basis and they reach back to the year 2003.

## Exercise 1: Pandas
In this exercise, print the DataFrame and you will notice that the format in which date has been provided as 161231 for 2016-12-31. Write a code to convert the 'date' to DateTime format.The resulting date should appear as '2016-01-01 01:00:00' based on your code.  You will need the hour field to build this.

## Exercise 2: Pandas
In this exercise, based on the total sum across time for each land, print the land parameter with the maximum traffic. You would be using indexing to indetify the land with those maximum traffic. Typically, you should be identifying the land with maximum traffic as one among the 16 values. 

## Exercise 3: Missing Values
The code below will randomly generate indeces and remove the data points from those indices. Using a technique of filling missing data, we will try to recover the lost data in the following exercise. 

### 3.1. In what conditions should NaN values be filled with mean and median? Please share your thoughts briefly.
(This is not going to count toward your grade. Hint: Consider outliers in the data)

### 3.2 Write the code to drop the rows with missing values

### 3.4 Fill the value with a constant

### 3.5 Fill the value with the mean of value above and below (time-wise) the datapoint

# Plot the line chart to identify the number of cars_r1 and cars_r2 vs. date with different colors and legends.

Using the `station` and `station_days`. Analyze what station and station_days represent and how they should be used. It is pretty straight forward.
The plots have been generated and given below for your reference. The code writtern should generate similar graphs. 

## Exercise 5: Plot the scatter plot for the top 3 busiest days per state
### Plot the different group of land vs. date and show the 3 busiest days using the below DataFrames generated.
Box plots and distribution plots are both very helpful in determining if the mean or median should be filled in with NaN values. It is not advised to use the mean to replace the missing values in a box plot if there are numerous or a big number of data points that behave as outliers since they will have a substantial impact on the mean. Since using mean values to fill in missing values may not produce a good model, it is disregarded. One can impute missing values using the mean value for symmetric data distribution. 
