# Mini Project 4: Page View Time Series Visualiser

## **1.0 Assignment**

For this project you will visualize time series data using a line chart, bar chart, and box plots. You will use Pandas, Matplotlib, and Seaborn to visualize a dataset containing the number of page views each day on the freeCodeCamp.org forum from 2016-05-09 to 2019-12-03. The data visualizations will help you understand the patterns in visits and identify yearly and monthly growth.

#### 1.0.1 Tasks
Use the data to complete the following tasks:

- Use Pandas to import the data from `"fcc-forum-pageviews.csv"`. Set the index to the `date` column.

- Clean the data by filtering out days when the page views were in the top 2.5% of the dataset or bottom 2.5% of the dataset.

- Create a `draw_line_plo`t function that uses Matplotlib to draw a line chart similar to `"examples/Figure_1.png"`. The title should be `Daily freeCodeCamp Forum Page Views 5/2016-12/2019.` The label on the x axis should be Date and the label on the y axis should be Page Views.

- Create a `draw_bar_plot` function that draws a bar chart similar to "examples/Figure_2.png". It should show average daily page views for each month grouped by year. The legend should show month labels and have a title of `Months.` On the chart, the label on the x axis should be `Years` and the label on the y axis should be `Average Page Views`.

- Create a `draw_box_plo`t function that uses Seaborn to draw two adjacent box plots similar to "examples/Figure_3.png". These box plots should show how the values are distributed within a given year or month and how it compares over time. The title of the first chart should be `Year-wise Box Plot (Trend)` and the title of the second chart should be `Month-wise Box Plot (Seasonality)`. Make sure the month labels on bottom start at Jan and the x and y axis are labeled correctly. The boilerplate includes commands to prepare the data.

# Results
### **Daily freeCodeCamp Forum Page Views 5/2016 - 12/2019**

![line_plot](https://user-images.githubusercontent.com/100784629/196314264-bd51a33e-2452-480b-a16f-00f317fe1adc.png)

### **Average Page Views By Months Group By Years**

![bar_plot](https://user-images.githubusercontent.com/100784629/196314536-2134a777-5906-433e-a60d-ce6a2858328c.png)


### **Year-wise Box Plot (Trend) & Month-wise Box Plot (Seasonality)**
![box_plot](https://user-images.githubusercontent.com/100784629/196314637-fdc2e0a4-ee43-4793-9b65-52b1a4667862.png)



