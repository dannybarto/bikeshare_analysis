
# Citibike
NYC Citibike with Tableau

## Purpose: 

- Use Tableau to import data and create worksheets, dashboards, and stories
- Utilize Tableau to portray the data in a visually professional and coherent way

## Overview of the statistical analysis:
The city of Des Moines, IA has requested bikeshare data to be analyzed to determine the feasibility of a bikeshare program there. Citibike data from New York City's program for the month of August 2019 was used to determine whether or not this would be a good investment for Des Moines.  

## Link to Tableau Story: 
[Tableau Story]

## Cleaning the Data:
Jupyter Notebook was used to change the trip duration data to a datetime field.
![Pic](https://github.com/dannybarto/bikeshare_analysis/blob/main/Challenge/images/date%20before.png?raw=true)

![Pic0](https://github.com/dannybarto/bikeshare_analysis/blob/main/Challenge/images/date_after.png?raw=true)

## Results of the NYC Citibikes Analysis:
For NYC, there were a few notableareas of interest.   Several trips originated outside the city center while. Users also tended to use routes that follow the river. 

### 1. Checkout Times for All Users
![Pic1](https://github.com/dannybarto/bikeshare_analysis/blob/main/Challenge/images/Checkout_Weekday_All_User%20Small.png?raw=true)

### 2. Checkout Times by Gender
![Pic2](https://github.com/dannybarto/bikeshare_analysis/blob/main/Challenge/images/Checkout_Weekday_Gender%20Small.png?raw=true)

### 3. Trips (Weekday per Hour)
![Pic3](https://github.com/dannybarto/bikeshare_analysis/blob/main/Challenge/images/Weekday_Trips_Hour%20Small.png?raw=true)

### 4. Trips by Gender (Weekday per Hour)
![Pic4] (https://github.com/dannybarto/bikeshare_analysis/blob/main/Challenge/images/Trips_Gender_Weekday_Hour%20Small.png?raw=true)

### 5. Trips by Gender and User Type (Weekday per Hour)
![Pic5](https://github.com/Baylex/Citibike/blob/main/Challenge/images/4_UserType.PNG)

### 6. Number of Rides per Hour
[Number of Rides per Hour](https://public.tableau.com/profile/julie.pyle2236#!/vizhome/Mod_14_Challenge/Rides)
Non-peak hours are 1-5 am.  
![Pic6](https://github.com/Baylex/Citibike/blob/main/Challenge/images/5_Rides.PNG)


### 7. Number of Rides with Bike ID
[Number of Rides with Bike ID](https://public.tableau.com/profile/julie.pyle2236#!/vizhome/Mod_14_Challenge/Repair)
The divergence line shows that there are high use on 1/3 of the bikes.
![Pic7](https://github.com/Baylex/Citibike/blob/main/Challenge/images/6_Repairs.PNG)

## Summary:

1. Bike Repairs for 1/3 of the Citibikes need to be done during non-peak hours around 1-5 am. 
2. Male subscribers are the highest users and follow the traditional high use times of travel to and from work.  
3. Target market should be males needing transportation to work and weekend activities and push for subscribing to the services. 

## Additional Analysis: 

For NYC, there were some interesting geographical areas of interest.  Some trips were outside the main city center.  Other areas followed the along the river. Future analysis would need to include a geographical review.

### 1. Ride Starting Locations by Gender
[Ride Starting Locations by Gender](https://public.tableau.com/profile/julie.pyle2236#!/vizhome/Mod_14_Challenge/Start)
Males are more likely to start a trip farther than the main city center of NYC than others. 
![Pic8](https://github.com/Baylex/Citibike/blob/main/Challenge/images/extra1.PNG)

### 2. Ride Ending Locations by Gender
[Ride Ending Locations by Gender](https://public.tableau.com/profile/julie.pyle2236#!/vizhome/Mod_14_Challenge/End)
Males are more likely end a trip across the river in the southwest area of NYC than others. 
![Pic9](https://github.com/Baylex/Citibike/blob/main/Challenge/images/extra2.PNG)

### 3. User Type Starting Location
[User Type Starting Location](https://public.tableau.com/profile/julie.pyle2236#!/vizhome/Mod_14_Challenge/UserTypeMap)
Subscribers are more likely to start trip farther than the main city center of NYC than others. 
![Pic10](https://github.com/Baylex/Citibike/blob/main/Challenge/images/extra3.PNG)
