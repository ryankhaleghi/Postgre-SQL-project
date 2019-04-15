# Postgre-SQL-project
This database was created for a fictional startup, Sparkify, to analyze user activity and song data in order to help understand what users are listening to. 

The data is contained in JSON files for the separate play logs and song data. I created a Postgres (SQL) database and ETL process to take data from those JSON files, process it into the Postgres database, and test it against queries from the Sparkify analytics team. 

The Postgres database utilizes a star schema with one fact and 4 dimension tables. The dimension tables store user data, song data, artist data, and play time data. The fact table is a composite of this data, showing the song played, when, by what user, their location, their method of access (web browser, phone, etc.) and their status as a paid or free user.
