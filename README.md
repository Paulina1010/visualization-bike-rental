# Visualization of bike rental data in London

This project provides some interesting visualizations on bike rentals in London. The data was downloaded from [kagle.com] (https://www.kaggle.com/hmavrodiev/london-bike-sharing-dataset) and includes information on the number of bike rentals, temperature, and wind speed and weather type.
The project transformed the data using the pandas library and then visualized the data using the matplotlib, seaborn, plotnine and ipywidgets libraries.

## Transformations
1. Split the timestamp column into date, time, month, year and day of the week.
2. Split the timestamp column into time of day.
3. Verify the occurrence of missing data.
4. Remove outliers.

## Visualization
1. Create a correlation matrix.
2. Scatterplot graph showing the relationship between temperature and the number of bikes rented.
3. Scatterplot showing the relationship between temperature, number of rentals and period of the week.
4. Line plot showing the average number of rentals per hour by holiday period and holidays and common days.
5. Bar plot showing the number of rentals by month by year
6. Boxplot chart showing the number of rentals by day of the week
7. Line plot showing rental hours by season
8. Scatterplot showing the dependence between temperature and rentals by year
9. Pie chart showing the percentage of rentals by type of weather
10. Violin plot of the dependence of the number of rentals on the type of weather.
11. Trend line graph of the number of bicycle rentals by time of day for each month.
12. Interactive graph that allows you to check the distribution for the desired variables with the selected type of graph (column graph, point graph, histogram or probability density graph)
13. Interactive chart that allows you to check the daily number of rentals in the selected year and month.
14. Interactive box plot that allows you to check the distribution of the number of bicycle rentals due to wind speed and selected temperature.

## Usage
The visuals can be previewed in the visualization_bike_rental.ipynb file. 

## Contributing
This project was done as part of a visualization skills exercise. If anyone would like to add new visualisation to this project then they can send a pull request.

## License
MIT, see [LICENSE](LICENSE)


