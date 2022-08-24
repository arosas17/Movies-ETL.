# Movies-ETL.

The general purpose of this assignment is to create a code that will take three files, organize it, and send it to a database. This code was built in four separate files, each one was added a little bit more code until the final code was made. It was also meant to be reusable so that if another set of ratings and list of movies were to be given, the data can be cleaned and usable in a short amount of time.

To clean the data, regular expression was used to detect data structured in particular manners and clean them. Some data was discarded, determining that the data would be difficult to fix and would add very little to the total data sets. After the data was cleaned to an acceptable level, the data is then sent to a database where it will reside as a table.

### Movies and Ratings Row Count
![movies_query.png](/Images/movies_query.png) ![ratings_query.png](/Images/ratings_query.png)

These tables are screenshots of the number of rows that were obtained after exporting to a database, the movies row count on the left and the ratings on the right. These counts suggest that everything was transferred correctly.

Two resource files are too large to attach.
