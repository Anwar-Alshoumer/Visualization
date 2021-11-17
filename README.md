# Visualization
Data exploration using Python  

## Dataset

> The data set includes information about individual rides made in a bike-sharing system from Ford GoBike system. It contains features related to three main aspects: bike and rides, customers and stations. The data collected for one month of Feb 2019.
> The dataset is constructed of 183412 rows and 16 columns which are: 

- duration_sec: with integer datatype,
- start_time: with object datatype, 
- end_time: with object datatype, 
- start_station_id: with float datatype, 
- start_station_name: with object datatype,
- start_station_latitude: with float datatype, 
- start_station_longitude: with float datatype, 
- end_station_id: with float datatype, 
- end_station_name: with object datatype, 
- end_station_latitude: with float datatype,
- end_station_longitude: with float datatype,
- bike_id: with integer datatype, 
- user_type: with object datatype,
- member_birth_year: with float datatype, 
- member_gender: with object datatype, 
- bike_share_for_all_trip: with object datatype, 


## Summary of Findings

> In the exploration, I investigated relationships between different features. I found that there was a negative correlation between age and duration. Then I wanted to check the relationship between gender and duration and found that female have longer duration among others. Then I tried user type and duration which showed that customers duration is longer than subscribers. After that I focused on the duration and time and if they are related based on user type and gender and found that customers tend to have long ride duration compared to subscribers, And they prefer afternoon riding while subscribers are mostly riding after midnight.
For start day, customers have longer duration specially on Sunday, while subscribers showed no much difference between days of the week.
Based on the hour of the day, males have shorter duration compared to others. The preferred start hour is varied between genders, the female have longest duration specially from 2 to 3 am.


## Key Insights for Presentation

> The presentation focus on identifying the common patterns for users, their favorite times for biking and ride duration. 
I used barplot for my visualizations which I found most clear visualization type as I focused on duration variable to support my investigation.
first visualization was to highlight duration and start hour based on user type, the second for relationship between duration and start day based on user type,
and the last one for relationship between duration and start hour based on gender. I make sure to use suitable colors, legend and clear labels and titles to make my visualizations clear and informative.
