# sqlalchemy-challenge
A new repository named **sqlalchemy-challenge** was created and cloned.
Inside the repository, a directory named **SurfsUp** was created for this Challenge.
The Jupyter notebook (climate_starter.ipynb) and Flask app (app.py) were added to the SurfsUp folder.
The Resources folder containing the **hawaii.sqlite** database file was included in the SurfsUp directory.
All changes were pushed to GitHub or GitLab repository.
**SQLAlchemy** was used to connect to the SQLite database, reflect tables, and save references to the station and measurement tables.
-- A precipitation analysis was performed: the last 12 months of precipitation data were queried, results were loaded into a Pandas DataFrame, and the data was plotted.
-- A station analysis was performed: the total number of stations was calculated, the most active station **USC00519281** was found, and temperature data for the last year for the station was queried.
-- A Flask API was designed with routes to return JSON data for precipitation, stations, temperature observations, and temperature statistics for specified date ranges.
The Flask app was deployed locally, and the API endpoints were tested to ensure they returned the correct data.
/api/v1.0/precipitation
/api/v1.0/stations
/api/v1.0/tobs
/api/v1.0/<start>
/api/v1.0/<start>/<end> 

### Miscellaneous
- func.max, func.min, and func.avg were used for calculations in SQLAlchemy queries.
- The SQLAlchemy session was closed at the end of the Jupyter notebook.
- The Flask jsonify function was used to convert data to JSON format.
- Code was commented for clarity and maintainability.
- Coding conventions were followed, and the code was properly formatted.