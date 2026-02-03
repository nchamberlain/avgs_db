# avgs_db
This library will contain the specialized database functionality for accessing historical temperature data for City Average Temperatures project (in process). It is specialized database functionality at this point because it will access a specific database (all_temps) with specific tables (<city_state> and <city_state_period>) with specific column names. This lib is NOT intended to be a general purpose db access program but instead is dedicated to the funtionality required by the Weatherxxx projects.

## Dependencies
Right now this lib will depend on the following crates:
-  sqlx
-  dotenvy

## API functions
- get_temps
-  list_cities
-  get_first_year
-  get_last_year
-  create_sub_tables
-  del_sub_tables
-  process_all_city_weather
