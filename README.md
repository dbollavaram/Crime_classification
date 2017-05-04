# Crime_classification
Crime classification using Neural nets, count featurizer

From 1934 to 1963, San Francisco was infamous for housing some of the world's most notorious criminals on the inescapable island of Alcatraz. Today, the city is known more for its tech scene than its criminal past. But, with rising wealth inequality, housing shortages, and a proliferation of expensive digital toys riding BART to work, there is no scarcity of crime in the city by the bay. From Sunset to SOMA, and Marina to Excelsior, this dataset provides nearly 12 years of crime reports from across all of San Francisco's neighborhoods.

This dataset was featured in our completed playground competition entitled San Francisco Crime Classification. The goals of the competition were to:

predict the category of crime that occurred, given the time and location
visualize the city and crimes (see Mapping and Visualizing Violent Crime for inspiration)
Content

This dataset contains incidents derived from SFPD Crime Incident Reporting system. The data ranges from 1/1/2003 to 5/13/2015. The training set and test set rotate every week, meaning week 1,3,5,7... belong to test set, week 2,4,6,8 belong to training set. There are 9 variables:

Dates - timestamp of the crime incident
Category - category of the crime incident (only in train.csv).
Descript - detailed description of the crime incident (only in train.csv)
DayOfWeek - the day of the week
PdDistrict - name of the Police Department District
Resolution - how the crime incident was resolved (only in train.csv)
Address - the approximate street address of the crime incident
X - Longitude
Y - Latitude
Acknowledgements


The original dataset is from SF OpenData, the central clearinghouse for data published by the City and County of San Francisco.

Description
Dates - timestamp of the crime incident
DayOfWeek - the day of the week
PdDistrict - name of the Police Department District
Address - the approximate street address of the crime incident
X - Longitude
Y - Latitude
