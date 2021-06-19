# MechaCar_Staistical_Analysis

UT Bootcamp Module 15 Challenge

## Project Overview
To research and analyze the miles per gallon and suspension coils data to provide statistical insights to the manufacturing team at MechaCar.

## Resources
Data provided for the project included the miles per gallon csv (MechaCar_mpg.csv) and the suspension coil csv (Suspension_Coil.csv) and then we ran statictics and reported the findings using the following applications:
- R (version 4.1.0)
- RStudio (version 1.4.1717)
- Personal Github account

## Analysis and Workflow 
Deliverable 1: Create a Linear Regression to Predict MPG (Six variables used - vehicle length, vehicle weight, spoiler angle, ground clearance, AWD, mpg) 
1. Use the library() function to load the dplyr package.
2. Import and read in the MechaCar_mpg.csv file as a dataframe.
3. Perform linear regression using the lm() function and pass in all six variables (i.e., columns), and add the dataframe you created to the data parameter.
4. Using the summary() function, determine the p-value and the r-squared value for the linear regression model.
5. Save your MechaCarChallenge.RScript file to your GitHub repository. 
### Linear Regression to Predict MPG
For this deliverable we are asked to provide answers to the following questions:
- Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?
Vatiables that show lower p-values provide a non-random amount of variance and have the greatest significance.  These would be the vehicle length and the ground clearance.
- Is the slope of the linear model considered to be zero? Why or why not?
- Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?

![alt text](https://github.com/austin020269/MechaCar_Staistical_Analysis/blob/main/Deli_1_Image.PNG)

Deliverable 2: Summary Statistics on Suspension Coils
1. Download the Suspension_Coil.csv file, and place it in the active directory for your R session.
2. In your MechaCarChallenge.RScript, import and read in the Suspension_Coil.csv file as a table.
3. Write an RScript that creates a total_summary dataframe using the summarize() function to get the mean, median, variance, and standard deviation of the suspension coil’s PSI column.
4. Write an RScript that creates a lot_summary dataframe using the group_by() and the summarize() functions to group each manufacturing lot by the mean, median, variance, and standard deviation of the suspension coil’s PSI column.
5. Save your MechaCarChallenge.RScript file to your GitHub repository.





## Summary Statistics on Suspension
