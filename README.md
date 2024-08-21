# Housing Prices Analysis and Visualization

This project involves analyzing housing price data from the OECD database and visualizing various aspects of the housing market across different countries, with a focus on Türkiye. The data manipulation and visualization processes involve the following steps:

1- Data Import and Initial Exploration:

- Import the dataset containing housing prices from the OECD database using Pandas.
- Conduct an initial exploration by displaying the first few rows and checking for missing values in the dataset.


2- Data Cleaning and Preparation:

- Select relevant columns, including Reference area, Measure, TIME_PERIOD, and OBS_VALUE.
- Filter out irrelevant data, such as records for a specific region (e.g., Israel).
- Sort the data by country (Reference area) and time period (TIME_PERIOD).


3- Calculating Year-Over-Year Percentage Change:

- Compute the year-over-year percentage change in housing prices for each country.
- Add a new column PCT_CHANGE to store these percentage changes.


4- Exploring Housing Price Measures:

- Identify unique measures in the dataset, such as 'Real house price indices' and 'Rent prices'.
- Group and analyze data to identify the highest and lowest housing prices for each year across different countries.


5- Country-Specific Analysis:

- Focus on specific countries, such as Türkiye, and analyze their housing price indices over time.
- Pivot the data to create a comprehensive view of various measures (e.g., price-to-income ratio, rent prices).


6- Data Visualization:

- Create visualizations to present insights, including:
- Bar Plots: Display top ten countries with the highest cumulative change in housing prices.
- Histograms: Show the distribution of rent prices.
- Line and Area Plots: Track the evolution of housing measures over time in specific countries.
- Pie Charts: Illustrate the ratio of increases and decreases in real house price indices in Türkiye.


7- Country-Specific Detailed Comparisons:

- Compare housing price indices and rent prices between Türkiye and the Euro area, and between Romania and Portugal.
- Analyze the data across different years and filter out specific periods where data is lacking.


8- Cumulative Analysis:

- Calculate and plot the cumulative sum of various housing measures over time for Türkiye.
- Evaluate the number of years with increases versus decreases in housing prices, represented in a pie chart.


This project leverages Python libraries such as Pandas, NumPy, Matplotlib, and Seaborn to clean, analyze, and visualize the data, providing comprehensive insights into housing price trends across multiple countries.
