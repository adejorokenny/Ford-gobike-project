## Ford Gobike Project

### About the dataset
The Ford gobike system dataset contains information about individual rides made in a bike-sharing system covering the greater San Francisco Bay area. The dataset contains 183,412 rows and 16 columns.
Some of the features of the dataset includes; duration_sec, start_station_name, start_station_id, end_station_name, end_station_id, bike_id, user_type, membe_birth_year, member_gender, bike_share_for_all_trip, etc.
The dataset can be downloaded using the [link](https://www.google.com/url?q=https://video.udacity-data.com/topher/2020/October/5f91cf38_201902-fordgobike-tripdata/201902-fordgobike-tripdata.csv&sa=D&source=editors&ust=1666883470330185&usg=AOvVaw0CK0e47azMi4eNPnKg8NDp)


### Libraries to install
- Numpy
- Pandas
- matplotlib.pyplot
- Seaborn

### Summary of Finding
* In this project, I explored some features of the dataset and observed that most of the members are of the male gender, I also discovered that the subscribers have the highest numbers of registered members when compared to the customers.
* Furthermore, the distribution plot of the member’s age shows that a large number of the members are of the age range 25-35 yrs old. It was also noticed by plotting the distribution plot of the ride duration in minutes that the most of the ride duration were less than 100 minutes.
* In addition, a deep dive plot was done for the member’s age to check for old members (60 yrs old and above) and teenagers (13 – 19 yrs old). The result showed that most of the old members are within the age range of 60 – 70years old, while almost all the teenagers are 19 years old except for a few.

### Key Insights for Presentation
* For the presentation, my primary focus was on the population count for some of the categorical variables to in order to understand people’s choice on the Ford gobike trip.
* I used the doughnut plots to visualize the value counts of the user type and member gender categories in order to have a clearer view of what the features represent since both features have two and three variables respectively. In addition, I made used of legend in order to distinguish what each color represent.
* Furthermore, I also looked at how the gender of members affected their choice. In order to accomplish this, I used the Violin plot to visualize the relationship between member gender and their age since the violin plot is perfect for checking relationship between a categorical and numerical variable. I also made use of the clustered bar chart to view the relationship between the member gender and the user type.
* Finally, I made use of the heatmap to view the relationship between the duration in minutes, member gender and user type. I added annotation to the plot in order to make the value of each column visible
