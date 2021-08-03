# Project-4-EDA

#Problem Statements:
#1.What are the top 5 zipcodes for 911 calls?

#2.What are the top 5 townships (twp) for 911 calls?

#3.Take a look at the 'title' column, how many unique title codes are there?

#4.In the titles column there are "Reasons/Departments" specified before the title code. These are EMS, Fire, and Traffic. Use .apply() with a custom lambda expression to create a new column called "Reason" that contains this string value.

#For example, if the title column value is EMS: BACK PAINS/INJURY , the Reason column value would be EMS.

#5.What is the most common Reason for a 911 call based off of this new column?

#6.Use seaborn to create a countplot of 911 calls by Reason.

#7.Use .apply() to create 3 new columns called Hour, Month, and Day of Week.

#8.Use the .map() with this dictionary to map the actual string names to the day of the week.

#9.Use seaborn to create a countplot of the Day of Week column with the hue based off of the Reason column.

#10.Create a simple plot off of the dataframe indicating the count of calls per month.

#** Note - Check if all months are available, if not, then use pandas to get the data

#11.Use seaborn's lmplot() to create a linear fit on the number of calls per month.
#** Note - you may need to reset the index to a column. **

#12.Create a plot of counts of 911 calls, but create 3 separate plots with each plot representing a Reason for the 911 call.
