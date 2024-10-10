
# Sales Analysis Per Hour
This project visualizes sales data by hour, showing how purchases are distributed throughout the day using Python's `matplotlib` library. It demonstrates how the number of purchases fluctuates at different times of the day.

## Dataset
The dataset used is `Order_details(masked).csv`, which contains details of transactions. The relevant information from the dataset includes the `Transaction Date`, which is processed to extract the hour at which each transaction occurred. 
The analysis focuses on counting the number of transactions for each hour of the day and visualizing these counts.
## How it Works
1. Data Preprocessing:
The Transaction Date column is first converted to a datetime object using pandas.
The hour of each transaction is extracted from the Transaction Date, allowing us to understand when the purchases occurred during the day.
The data is aggregated to count the number of transactions for each hour (from 0 to 23).
2. Visualization:
A line graph is generated using matplotlib to visualize the number of purchases made during each hour of the day.
The line plot shows cumulative purchases for each hour, and points are marked to highlight each hour's data clearly.
The project answers questions like:

What time of day are purchases most frequent?
Are there any periods of high activity?

## Requirements
Python 3.x
matplotlib
pandas
numpy
