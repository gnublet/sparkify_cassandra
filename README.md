# Sparkify - Cassandra
ETL music app historical data into Cassandra

## Files
CassandraProject.ipynb 
* Load original event csv data files into a new event_datafile_new.csv file for non-empty artist fields.
* Create cassandra "udacity" keyspace for the tables
* Create Cassandra tables for 3 queries:
    * artist, song_title, song_length in music app history given sessionid and iteminsession
    * artist, song, first_name, last_name given user_id, sessionid
    * first_name, last_name given song
