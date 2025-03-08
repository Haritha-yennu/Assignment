# Assignment
This repository contains three assignments focused on data analysis using PySpark. Each assignment demonstrates different aspects of data manipulation, extraction, and visualization using PySpark DataFrames. Below are the details of each assignment.

**Assignment 1: Movie Ratings Analysis**
Objective: Analyze a dataset of movie ratings to derive insights about user behavior and movie performance.

**Key Steps:**

Data Generation: A synthetic dataset is created with the schema: MovieID, User ID, Rating, and Timestamp.
Data Loading: The dataset is loaded into a PySpark DataFrame for analysis.
Average Rating Calculation: The average rating for each movie is computed.
User Activity Identification: Users who have rated more than 5 movies are identified.
Top Movies Determination: The top 5 highest-rated movies are determined based on average ratings.
Visualization: A bar chart is generated to visualize the number of movies rated by each user.
Technologies Used: PySpark, Pandas, Matplotlib

**Assignment 2: Trip Data Analysis**  
Objective: Analyze trip data to understand trip durations, fares, and patterns in trip activity.

**Key Steps:**

Data Generation: A small dataset is created with the schema: TripID, StartTime, EndTime, Distance, and Fare.
Data Loading: The dataset is loaded into a PySpark DataFrame.
Trip Duration Calculation: The duration of each trip is calculated based on start and end times.
Average Fare Calculation: The average fare per mile is computed.
Longest Trips Identification: The top 3 longest trips based on distance are identified.
Hourly Trip Count: Trips are grouped by hour, and the total number of trips per hour is calculated and visualized.
Technologies Used: PySpark, Matplotlib

**Assignment 3: Log Analysis**
Objective: Analyze log data to extract meaningful insights regarding application behavior and error occurrences.

**Key Steps:**

Log File Generation: A log file is created with various log entries, including timestamps, log levels (INFO, ERROR), and messages.
Data Loading: The log file is loaded into a PySpark DataFrame.
Data Extraction: The timestamp, log level, and message are extracted from the log entries.
Log Level Count: The number of occurrences of each log level is counted.
Error Log Filtering: Only ERROR logs are filtered and displayed.
Hourly Log Count: Logs are grouped by hour, and the total number of logs in each hour is calculated.
Technologies Used: PySpark, Matplotlib
