MechaCar_Staistical_Analysis

UT Bootcamp Module 15 Challenge

## Project Overview
To research and analyze the miles per gallon and suspension coils data to provide statistical insights to the manufacturing team at MechaCar.

## Resources
Data provided for the project included the miles per gallon csv (MechaCar_mpg.csv) and the suspension coil csv (Suspension_Coil.csv) and then we ran statictics and reported the findings using the following applications:
- R (version 4.1.0)
- RStudio (version 1.4.1717)
- Personal Github account

## Analysis and Workflow 
Deliverable 1: Create a Linear Regression to Predict MPG
1. Use the library() function to load the dplyr package.
2. Import and read in the MechaCar_mpg.csv file as a dataframe.
3. Perform linear regression using the lm() function and pass in all six variables (i.e., columns), and add the dataframe you created to the data parameter.
4. Using the summary() function, determine the p-value and the r-squared value for the linear regression model.
5. Save your MechaCarChallenge.RScript file to your GitHub repository. 

Pandas code:

![alt text](https://github.com/austin020269/biksharing/blob/main/CH1_Deli1.PNG)
![alt text](https://github.com/austin020269/biksharing/blob/main/CH1_Deli1_2.PNG)

New data created to use in Tableau:

![alt text](https://github.com/austin020269/biksharing/blob/main/Cleaned_data_Aug_2019.PNG)

Deliverable 2:  For the following displays gender (number) sequences in the "Number of String" legends are female (2), male (1) and unknown (0).
1. There is a line graph displaying the number of bikes checked out by duration for all users, and the graph can be filtered by the hour.
![alt text](https://github.com/austin020269/biksharing/blob/main/Deli2_1.PNG)

2. There is a line graph displaying the number of bikes that are checked out by duration for each gender by the hour, and the graph can be filtered by the hour and gender.
![alt text](https://github.com/austin020269/biksharing/blob/main/Deli2_2.PNG)

3. A heatmap is created showing the number of bike trips for each hour of each day of the week.
![alt text](https://github.com/austin020269/biksharing/blob/main/Deli2_3.PNG)

4. A heatmap is created showing the number of bike trips by gender for each hour of each day of the week, and the heatmap can be filtered by gender.
![alt text](https://github.com/austin020269/biksharing/blob/main/Deli2_4.PNG)

5. A heatmap is created showing the number of bike trips for each type of user and gender for each day of the week, and you can only filter by user and gender.
![alt text](https://github.com/austin020269/biksharing/blob/main/Deli2_5.PNG)

Deliverable 3: Results

Some of the conclusions that can be drawn from the products that were made during this project include:

- Males are the largest users of the service which is backed by all data products.
- Most bike rides are between 3 and 15 minutes for both males and females (Deli 2 Image 1 and 2).
- Weekends show more consistent riding during the days while weekdays show peak hours before and after work during high commute times (Deli 2 Image 3 and 4)
- The greatest usage of the service is by males with the most usage on Thursdays and Fridays.

Further details of this study can be seen on the Tableau public dashboards : 

https://public.tableau.com/app/profile/jeffrey.keith.austin/viz/NYCCitiBikeStudy_16229476255070/Story1
https://public.tableau.com/app/profile/jeffrey.keith.austin/viz/NYCCitiBikeStudyadditionaldata/Story1
