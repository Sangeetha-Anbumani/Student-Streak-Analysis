# Student Streaks Analysis with SQL

Objective:
The objective of this project is to calculate each user's most extended streak length. The streak length increments each day the user remains active, without manually freezing their streak to preserve progress. The length is not extended when there are no new daily interactions or when the streak is frozen.

Database Structure:
The MySQL database provided for this project contains a `user_streaks` table with the following fields:
- `streak_id`: Unique identifier for each streak record
- `user_id`: Identifier for each user
- `streak_active`: Boolean field indicating if the streak is currently active (True) or not (False)
- `streak_frozen`: Boolean field indicating if the streak is currently frozen (True) or not (False)
- `streak_platform`: The platform on which the streak was recorded
- `streak_created`: The date when the streak was started or updated

SQL Query:
The SQL query used for this project calculates each user's most extended streak length. It initializes variables, calculates streak lengths, and identifies the most extended streak for each user.

How to Use:
1. Set up a MySQL database and import the provided `user_streaks` table.
2. Copy the SQL query provided in this project and execute it in your MySQL environment.
3. The query will generate a result containing each user's ID and their corresponding maximum streak length.

   
Completed as part of the Advance SQL course on the 365 Data Science website.

