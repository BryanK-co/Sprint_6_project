# Sprint_6_project
Introduction:
This project aims to analyze taxi ride data in Chicago for the month of November 2017. The analysis focuses on various aspects such as the number of rides provided by different taxi companies, the most popular drop-off locations, and the impact of weather conditions on ride durations. By examining these factors, we can gain insights into the performance of taxi services, the preferences of passengers, and the influence of external conditions on travel times.

The data used in this project includes:
•	chicago_weather_nov_2017.csv`: Weather data for Chicago in November 2017.
•	comp_name_01.csv`: Data on taxi companies and the number of rides they provided.
•	drop_loc_04.csv`: Data on drop-off locations and the average number of trips.
•	duration_07.csv`: Data on ride durations and weather conditions.

The data was cleaned by:
•	Removing rows with missing values.
•	Dropping duplicate rows.
•	Converting date columns to datetime format.
•	Ensuring the correct data types for each column.


## Analysis
The analysis includes:
•	Top 10 Taxi Companies by Number of Rides: A bar plot showing the top 10 taxi companies based on the number of rides they provided.
•	Top 10 Neighborhoods by Number of Drop-offs: A bar plot showing the top 10 neighborhoods based on the average number of drop-offs.
•	Hypothesis Testing: A two-sample t-test to compare the average duration of rides from the Loop to O'Hare International Airport on rainy and non-rainy Saturdays.
•	Ride Duration Comparison: A box plot and line plot comparing the ride durations on rainy and non-rainy Saturdays.


Conclusion
The analysis highlights the dominance of certain taxi companies and neighborhoods in terms of ride volumes, as well as the significant impact of weather conditions on ride durations. These insights can be valuable for taxi companies, city planners, and policymakers to improve transportation services and infrastructure in Chicago.

Requirments
- Python 3.x
- pandas
- numpy
- seaborn
- matplotlib
- scipy

usage
1. Clone the repository.
2. Install the required packages.
3. Run the Jupyter Notebook to perform the analysis.
