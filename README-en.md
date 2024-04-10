# Project-6

## Project description
On this project I'm working as an analyst at Zuber, a new ride-sharing company launching in Chicago. My task is to find patterns in the available information. I want to understand passenger preferences and the impact of external factors on rides.  
Working with a database, i will analyze competitor data and test a hypothesis about the impact of weather on travel frequency.

## Data description
A database with information about taxi rides in Chicago:

`neighborhoods` table: data about the city’s neighborhoods
- `name`: name of the neighborhood
- `neighborhood_id`: neighborhood code

`cabs` table: data about taxis
- `cab_id`: vehicle code
- `vehicle_id`: the technical identification of the vehicle
- `company_name`: company that owns the vehicle

`trips` table: data about races
- `trip_id`: race code
- `cab_id`: code of the vehicle operating the race
- `start_ts`: date and time of the start of the race (time closed to the time)
- `end_ts`: date and time of the end of the race (time closed to the time)
- `duration_seconds`: duration of the race in seconds
- `distance_miles`: distance traveled in miles
- `pickup_location_id`: pickup neighborhood code
- `dropoff_location_id`: delivery neighborhood code

`weather_records` table: weather data
- `record_id`: meteorological record code
- `ts`: recording date and time (time closed to the time)
- `temperature`: temperature when the recording was made
- `description`: brief description of the dangerous conditions, e.g. "light rain" or "scattered clouds"

## Libraries
- pandas
- numb
- spicy
  
Note: This project was developed based on the guidance I received to improve my logical reasoning as a student. As a result, we even maintain all requested orders related to guidance for carrying out the necessary calculations.
