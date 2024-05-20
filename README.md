# Data Science Internship Task 5
<br>
<img src="https://github.com/kindo-tk/PRODIGY_DS_05/blob/main/ds5.png">

Welcome to the repository for my traffic accident data analysis project, completed during my data science internship at `Prodigy Infotech`. This project involves data cleaning, exploratory data analysis (EDA), visualization, and deriving insights from a dataset containing traffic accident records.

## Project Overview

The goal of this project is to analyze traffic accident data to understand patterns and trends, identify accident hotspots, and provide actionable insights that can help in enhancing road safety measures.

## Data Description

The <a href = "https://www.kaggle.com/datasets/sobhanmoosavi/us-accidents">`dataset`</a> used in this analysis contains the following attributes:

| Attribute              | Description                                                                                     |
|------------------------|-------------------------------------------------------------------------------------------------|
| ID                     | This is a unique identifier of the accident record.                                             |
| Severity               | Shows the severity of the accident, a number between 1 and 4, where 1 indicates the least impact and 4 indicates the most significant impact on traffic.|
| Start_Time             | Shows start time of the accident in local time zone.                                            |
| End_Time               | Shows end time of the accident in local time zone.                                              |
| Start_Lat              | Shows latitude in GPS coordinate of the start point.                                            |
| Start_Lng              | Shows longitude in GPS coordinate of the start point.                                           |
| End_Lat                | Shows latitude in GPS coordinate of the end point.                                              |
| End_Lng                | Shows longitude in GPS coordinate of the end point.                                             |
| Distance(mi)           | The length of the road extent affected by the accident.                                         |
| Description            | Shows natural language description of the accident.                                             |
| Number                 | Shows the street number in the address field.                                                   |
| Street                 | Shows the street name in the address field.                                                     |
| Side                   | Shows the relative side of the street (Right/Left) in address field.                            |
| City                   | Shows the city in the address field.                                                            |
| County                 | Shows the county in the address field.                                                          |
| State                  | Shows the state in the address field.                                                           |
| Zipcode                | Shows the zipcode in the address field.                                                         |
| Country                | Shows the country in the address field.                                                         |
| Timezone               | Shows timezone based on the location of the accident (eastern, central, etc.).                  |
| Airport_Code           | Denotes an airport-based weather station which is the closest one to the location of the accident.|
| Weather_Timestamp      | Shows the time-stamp of the weather observation record (in local time).                         |
| Temperature(F)         | Shows the temperature (in Fahrenheit).                                                          |
| Wind_Chill(F)          | Shows the wind chill (in Fahrenheit).                                                           |
| Humidity(%)            | Shows the humidity (in percentage).                                                             |
| Pressure(in)           | Shows the air pressure (in inches).                                                             |
| Visibility(mi)         | Shows visibility (in miles).                                                                    |
| Wind_Direction         | Shows wind direction.                                                                           |
| Wind_Speed(mph)        | Shows wind speed (in miles per hour).                                                           |
| Precipitation(in)      | Shows precipitation amount in inches, if any.                                                   |
| Weather_Condition      | Shows the weather condition (rain, snow, thunderstorm, fog, etc.).                              |
| Amenity                | A POI annotation indicating the presence of an amenity in a nearby location.                    |
| Bump                   | A POI annotation indicating the presence of a speed bump or hump in a nearby location.          |
| Crossing               | A POI annotation indicating the presence of a crossing in a nearby location.                    |
| Give_Way               | A POI annotation indicating the presence of a give_way in a nearby location.                    |
| Junction               | A POI annotation indicating the presence of a junction in a nearby location.                    |
| No_Exit                | A POI annotation indicating the presence of a no_exit in a nearby location.                     |
| Railway                | A POI annotation indicating the presence of a railway in a nearby location.                     |
| Roundabout             | A POI annotation indicating the presence of a roundabout in a nearby location.                  |
| Station                | A POI annotation indicating the presence of a station in a nearby location.                     |
| Stop                   | A POI annotation indicating the presence of a stop in a nearby location.                        |
| Traffic_Calming        | A POI annotation indicating the presence of traffic calming measures in a nearby location.       |
| Traffic_Signal         | A POI annotation indicating the presence of a traffic signal in a nearby location.              |
| Turning_Loop           | A POI annotation indicating the presence of a turning loop in a nearby location.                |
| Sunrise_Sunset         | Shows the period of day (i.e. day or night) based on sunrise/sunset.                            |
| Civil_Twilight         | Shows the period of day (i.e. day or night) based on civil twilight.                            |
| Nautical_Twilight      | Shows the period of day (i.e. day or night) based on nautical twilight.                         |
| Astronomical_Twilight  | Shows the period of day (i.e. day or night) based on astronomical twilight.                     |

## Methodology

1. **Data Cleaning**: Handled missing values, converted data types, and ensured consistency across the dataset.
2. **Exploratory Data Analysis (EDA)**: Analyzed the distribution and relationships of key variables to uncover patterns and insights.
3. **Visualization**: Created various plots and charts to visually represent the data and findings.

## Key Findings

- **City-wise Distribution**: Miami is the city with the most number of accidents, while Star Junction and Stromsburg have the least.
- **State-wise Distribution**: California has the highest number of accidents, whereas South Dakota has the least.
- **Yearly Trends**: The year 2021 saw the highest number of accidents.
- **Severity Levels**: Most accidents were classified at severity level 2.
- **Weather Conditions**: The majority of accidents occurred under fair weather conditions.
- **Time of Day**: Most accidents happened in the morning.

## Conclusion

This analysis highlights key patterns in traffic accident data, such as high accident rates in densely populated areas like Miami and California, and a significant number of accidents occurring under fair weather conditions in the morning. These insights can inform road safety initiatives and policy decisions to reduce accidents and improve public safety.

## Contact Information
For any inquiries or feedback regarding this project, please contact:

- <a href="https://www.linkedin.com/in/tufan-kundu-577945221/">Tufan Kundu (LinkedIn)</a>
- Email: tufan.kundu11@gmail.com


