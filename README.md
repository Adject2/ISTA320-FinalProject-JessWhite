# ISTA320-FinalProject-JessWhite
My final project for ISTA320, based on data collected from PlateRunner, a car spotting game (which I made) that uses NHTSA vehicle data to log vehicles that you see.

# The Purpose
This project will create several visualizations of data collected on local cars, based on the following set of questions.

**Timeseries scatter plot**: 
What is the average age of the cars that are on the road today? What are the newest and oldest cars still driving?

**Bar graph**: 
Which car manufacturer is the most popular here in Tucson? From that manufacturer, which model is the most popular?

**World map**: 
Where do these cars originate from? What is the most popular country of origin? In general, where are the local cars coming from and in what distribution?

# The Data
All of this data is collected from a game I made that interacts with vinfreecheck.com to gather basic data on cars. The data I have collected, with the help of a few friends, represents a large sample of cars from my local area in Vail and South Tucson. Originally stored in a .plate file (a data structure I made up similar to .csv), I have rewritten the data into a CSV file for use in this project.

The data contains the ID of a player who found the vehicle, the plate number, the VIN number, the make, the model, the year, the trim (if applicable), the engine specifications, the country of origin, and a nickname for the vehicle (if applicable). I will only be using the make, model, year, and country of origin in this project.
