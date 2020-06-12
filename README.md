# Coronadata

I read an article that suggested that mortality rate was heavily related with access to medical attention and hospital beds.
I attempted to see if there is a correlation between hospital bed access and mortality rate.

# Data set made up of three combined data sets:
-deaths/critical care/minimal care from corona/ state and day (IHME web page)
-number of staffed beds/ state (Statista web page)
-population/ state (worldometer web page)
# process 
All three graphs contained differing amounts of informations and orders, so the hardest part was getting them to line up.
first I used and 'isin' function to only take the information from each table that was in the others. I then had to order them appropriately using many techniques including dictionaries and looping functions. I then appended them together, and did the math to get the additional rows that showed what i wanted them to. 

# results
first graph shows all data and has a correlation of -.3
second graph is more zoomed in, removing outliers. It has a correlations of -.26

# conclusion

The correlation is negative. This means that the more people per medically staffed bed the state has access to, the lower the mortality rate. This is contradictory to what I thought it would look like.
My theory: The y value is not depended on the x value. They are both independent (or close to it), but are both dependent to one of two variables: 
-In general, places that are more prone to injury or sickness (possibly due to high population density) will need more staffed hospital beds in general to deal with the high number of sickness/injury. The corona virus is no different. States that are more "prone" to sickness are also the same states that are prepared with more staffed beds. → example: New York (highest death ratio).
-Places with smaller populations, such as the Midwest, are easier to staff. However, they also may not have the same ability to access the same quality medical care that some of the larger, wealthier states may. → Example: Alabama (third to highest death ratio)

