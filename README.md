# bikesharing

## Overview of the analysis:

* The goal of this analysis is to solidify the proposal for investors and convice them that a bike-sharing program in Des Moines is a solid business proposal. To solidify the proposal, one of the key stakeholders would like to see a bike trip analysis.

* For this analysis, I used Pandas to change the "tripduration" column from an integer to a datetime datatype. Then, using the converted datatype, I created a set of visualizations to:
  - Show the length of time that bikes are checked out for all riders and genders
  - Show the number of bike trips for all riders and genders for each hour of each day of the week
  - Show the number of bike trips for each type of user and gender for each day of the week.

* Finally, I added these new visualizations to the two I created for my final presentation and analysis to pitch to investors.

* Last but not least, this report includes two technical analysis deliverables and a written report to present my results. 
  - Deliverable 1: Change Trip Duration to a Datetime Format
  - Deliverable 2: Create Visualizations for the Trip Analysis
  - Deliverable 3: Create a Story and Report for the Final Presentation

## Change Trip Duration to a Datetime Format

For this analysis, I used Pandas to convert the "tripduration" column from an integer to a datetime datatype and converted datatype as seen below. Also, the DataFrame is exported as a new file without the index column.

!['tripduration'%20column%20to%20datetime](https://github.com/cbrito3/bikesharing/blob/main/Visualization/'tripduration'%20column%20to%20datetime.png)

!['datatypes%20of%20your%20columns](https://github.com/cbrito3/bikesharing/blob/main/Visualization/datatypes%20of%20your%20columns.png)

Then, using the converted datatype, I created a set of visualizations to:
Show the length of time that bikes are checked out for all riders and genders
Show the number of bike trips for all riders and genders for each hour of each day of the week
Show the number of bike trips for each type of user and gender for each day of the week.
Finally, you’ll add these new visualizations to the two you created in this module for your final presentation and analysis to pitch to investors.

## Results: 
This first visualization shows the length of time of every bike ride during the month of August in 2019. This information allows us to see that riders typically like to bike between 2 and 15 minutes.

!['Checkout%20time%20by%20Users](https://github.com/cbrito3/bikesharing/blob/main/Visualization/Checkout%20time%20by%20Users.png)

This second visualization shows the breakdown of riders by gender and duration of times. This shows that most of the users are men.

!['Checkout%20time%20by%20Gender](https://github.com/cbrito3/bikesharing/blob/main/Visualization/Checkout%20time%20by%20Gender.png)

This third visualization shows user trips by weekdday for each hour of the day as a heatmap.. This shows that from a weekday perspective trips are most common on Thursdays afternoon between 5pm and 6pm.  

!['Trips%20by%20Weekday%20Per%20Hour%20](https://github.com/cbrito3/bikesharing/blob/main/Visualization/Trips%20by%20Weekday%20Per%20Hour%20.png)

This forth visualization shows trips by gender (Weekday per Hour), the graph is the number of bike trips by gender for each hour of each day of the week as a heatmap. This shows that the most common user are male subscribers and from a weekday perspective they frequently ride bikes on Thursdays in the afternoon between 5pm and 6pm. 
!['Trips%20by%20Gender%20(Weekday%20per%20Hour)%20](https://github.com/cbrito3/bikesharing/blob/main/Visualization/Trips%20by%20Gender%20(Weekday%20per%20Hour)%20.png))

This fifth visualization shows user trips by gender by Weekday. In this visualization, the heatmap  shows the number of bike trips broken down by gender for each day of the week by each Usertype. 

!['Trips%20by%20Gender%20by%20Weekday](https://github.com/cbrito3/bikesharing/blob/main/Visualization/Trips%20by%20Gender%20by%20Weekday.png)

These two visualizations that we created in this module, the top starting and ending locations, provide other useful information. 
In the first visualization we note that  most rides start in the most populous areas in mid and lower Manhattan. 
!['The%20Top%20Bike%20Stations%20in%20the%20City%20for%20Starting%20a%20Journey](https://github.com/cbrito3/bikesharing/blob/main/Visualization/The%20Top%20Bike%20Stations%20in%20the%20City%20for%20Starting%20a%20Journey.png)

This second visualization, due to shorter ride times, shows that the ending locations are also in those same populous areas.
!['The%20Top%20Bike%20Stations%20for%20Ending%20a%20Journey](https://github.com/cbrito3/bikesharing/blob/main/Visualization/The%20Top%20Bike%20Stations%20for%20Ending%20a%20Journey.png)

## Summary: Provide a high-level summary of the results and two additional visualizations that you would perform with the given dataset.

Based on the data visualization results we can recommend that a bike-sharing program in Des moine is indeed a solid business proposal. Some recommendations are: 
- Placing bikes in areas/neighborhoods that are populous and people love the bike-sharing experience.
- While women are common bike users, their commitment is not as that as men, this should not be a reason to exclude them from any advertising and marketing promotions and strategies. Both men and women should be considered as main targets and the goal should be how to increase usage numbers in general. 


## Tableau Links is below:

[link to dashboard](https://public.tableau.com/app/profile/claudia.brito/viz/bikesharing_16633150771410/Bikesharestory?publish=yes)

