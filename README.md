# Business Objective
This project aims to utilize historical data from car accidents and apply machine learning to predict severity of the accident. Car accident data can help us understand the potential situations where certain type of accidents can happen. In this project, car accident data from 2016 to 2021 are analyzed and machine learning models were used in order to see which model provides best fit to the data. Outcome of this project can be used by goverment authorities as well as private companies for improving road conditions, and developing products for suggesting safer routes in a given road condition. For example, knowing conditions like visibility and precipitation, etc, a route suggesting application like Google Map or Waze can give recommendation to the user based on the potential accident that can happen for travelling from point A to point B. 

# Source Data
Source data is from Kaggle. It contains 2,845,342 rows and 47 columns. List of column names are provided below:


'ID', 'Severity', 'Start_Time', 'End_Time', 'Start_Lat', 'Start_Lng',
       'End_Lat', 'End_Lng', 'Distance(mi)', 'Description', 'Number', 'Street',
       'Side', 'City', 'County', 'State', 'Zipcode', 'Country', 'Timezone',
       'Airport_Code', 'Weather_Timestamp', 'Temperature(F)', 'Wind_Chill(F)',
       'Humidity(%)', 'Pressure(in)', 'Visibility(mi)', 'Wind_Direction',
       'Wind_Speed(mph)', 'Precipitation(in)', 'Weather_Condition', 'Amenity',
       'Bump', 'Crossing', 'Give_Way', 'Junction', 'No_Exit', 'Railway',
       'Roundabout', 'Station', 'Stop', 'Traffic_Calming', 'Traffic_Signal',
       'Turning_Loop', 'Sunrise_Sunset', 'Civil_Twilight', 'Nautical_Twilight',
       'Astronomical_Twilight'



# Goal
We want to use parameters that are captured in this dataframe for each accident to come up with a model that can predict severity of the accident. Per database source (Bing and MapQuest), severity in this dataset is based on the impact of the accident to the traffic flow. Based on Bing's definition of the severity, 4 levels are defines as below:
- 1: LowImpact
- 2: Minor
- 3: Moderate
- 4: Serious

# Method

