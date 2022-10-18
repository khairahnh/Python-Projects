# Mini Project 5 : Sea Level Predictor

## **1.0 Assignment**
You will analyze a dataset of the global average sea level change since 1880. You will use the data to predict the sea level change through year 2050.

## **1.1 Tasks**
Use the data to complete the following tasks:

- Use Pandas to import the data from `epa-sea-level.csv.`
- Use matplotlib to create a scatter plot using the `Year` column as the x-axis and the `CSIRO Adjusted Sea Level` column as the y-axix.
-Use the l`inregress` function from `scipy.stats` to get the slope and y-intercept of the line of best fit. Plot the line of best fit over the top of the scatter plot. Make the line go through the year 2050 to predict the sea level rise in 2050.
- Plot a new line of best fit just using the data from year 2000 through the most recent year in the dataset. Make the line also go through the year 2050 to predict the sea level rise in 2050 if the rate of rise continues as it has since the year 2000.
- The x label should be `Year`, the y label should be `Sea Level` (inches), and the title should be `Rise in Sea Level`.

## **Results**

![sea_level_plot](https://user-images.githubusercontent.com/100784629/196317497-d322e8fd-3a87-4472-b6ad-fb0ef1bab819.png)
