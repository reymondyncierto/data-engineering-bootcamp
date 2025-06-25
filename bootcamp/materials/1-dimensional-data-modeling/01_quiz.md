What are 'struct' and 'array' considered as in dimensional data modeling?

a. They are coding structures
b. They are basic data types
c. They are simple aggregations
d. They are complex data types

Explanation: Struct and array are considered complex data types because they allow for more detailed and compact storage of data, essential for modeling complex datasets.

Which of the following is a characteristic of a slowly changing dimension?

a. It changes frequently
b. It is time-dependent
c. It never changes
d. It lacks historical data

Explanation: A slowly changing dimension is time-dependent because it has attributes that can change over time, like a person's favorite food, reflecting different states at different times.

What is the purpose of the cumulative table design in data modeling?

a. To remove all historical data
b. To eliminate duplicate data completely
c. To hold onto all dimensions that ever existed
d. To sort data in ascending order

Explanation: Cumulative table design aims to keep a comprehensive history of all data, ensuring that any previous data is not lost, which is crucial for historical analysis.

In the context of dimensional data modeling, who would likely benefit the most from an OLAP cube?

a. Financial Accountants
b. Data Scientists and Analysts
c. Software Engineers
d. Customer Support Representatives

Explanation: Data scientists and analysts benefit from OLAP cubes because they provide an easy-to-use format for quick analytical queries without needing complex joins.

What is a potential drawback of cumulative table design?

a. It cannot store user activities
b. It cannot handle historical analysis
c. It relies on yesterday's data for continuity
d. It's easy to backfill parallelly

Explanation: A drawback is that cumulative table design depends on sequential processing where today's data depends on yesterday's data, making parallel backfilling difficult.

Why is the player seasons table considered inefficient according to the workshop?


a. It contains incomplete statistical data
b. It lacks player identification information
c. It requires frequent schema changes
d. It has too many temporary components that reduce compression

Explanation: The table has temporal issues causing shuffling and loss of compression, which the workshop seeks to address.

What data type is used in the workshop to store multiple attributes like games played and points?

a. REAL
b. STRUCT
c. INTEGER
d. TEXT

Explanation: The STRUCT data type is used to store season-related attributes as a unified type in the model.

What is the purpose of creating a 'season stats' struct in PostgreSQL as discussed in the lab?

a. To aggregate player statistics and improve data compression
b. To convert all statistics to integers
c. To introduce redundancy in the data table
d. To separate player names from their attributes

Explanation: The 'season stats' struct aggregates player statistics into one data type, improving data compression and handling temporal components better.

What SQL function is utilized to convert an array column back to a series of rows efficiently as demonstrated in the lab?
a. UNNEST
b. CONCAT
c. JOIN
d. GROUP BY

Explanation: The UNNEST function is used to expand an array into a set of rows, making it possible to analyze the array's elements as individual records.
