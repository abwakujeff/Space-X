Dataset  
The dataset used is SpaceX_Falcon9.csv, which includes the following columns:  

FlightNumber: Identifier for the flight  
Date: Date of the flight  
BoosterVersion: Version of the booster used  
PayloadMass: Mass of the payload  
Orbit: Orbit type for the mission  
LaunchSite: Launch site of the mission  
Outcome: Outcome of the landing  
Flights: Number of flights  
GridFins: Whether grid fins were used  
Reused: Whether the booster was reused  
Legs: Whether the landing legs were deployed  
LandingPad: Landing pad used  
Block: Block of the booster  
ReusedCount: Count of times the booster was reused  
Serial: Serial number of the booster  
Longitude: Longitude of the landing site  
Latitude: Latitude of the landing site  

**Objectives**  
**Exploratory Data Analysis (EDA)**  

Check DataFrame values, missing values, and generate necessary variables.  
Import libraries, load the dataset, and perform initial inspections.  
Data Cleaning and Preparation  

Identify and handle missing values.  
Create a new variable landing_class to indicate whether the landing was successful (1) or not (0).  
**Analysis**    

Compare success rates by different groups, such as orbit and launch site.  
Examine the success rate based on whether the booster was reused or not.  

**Key Insights**
Missing Values: Identify missing values and their percentages.  
Success Rate by Orbit: Calculate the success rate of landings for each orbit type.  
Launch Site Analysis: Determine the number of launches and success rates for each launch site.  
Reused Booster Analysis: Analyze the impact of booster reuse on landing success.  
