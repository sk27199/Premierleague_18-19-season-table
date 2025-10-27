**Premier League 2018/19 SQL Project**

**Overview**

This project is based on the 2018/19 Premier League season.
I created a database table using SQL to store every team’s results — including matches played, wins, losses, goals, and points.

The goal was to practice database design, data entry, and SQL queries using real-world football data. It helped me understand how to structure data properly and how to get useful information back using queries.

**What I Did**

Created a table called premierleague_1819 using CREATE TABLE

Added columns for things like team name, wins, goals, and points

Inserted data for all 20 Premier League teams from the 2018/19 season

Used SELECT, WHERE, and ORDER BY statements to explore and analyze the data

**Example Queries**
-- View the full league table
SELECT * FROM premierleague_1819;

-- Show the top 5 teams
SELECT team_name, points FROM premierleague_1819 ORDER BY points DESC LIMIT 5;

-- Find teams that scored more than 70 goals
SELECT team_name, goals_for FROM premierleague_1819 WHERE goals_for > 70;

-- Check which teams were relegated
SELECT team_name, points FROM premierleague_1819 WHERE position > 17;

**What I Learned**

This project taught me:

How to create and structure a database table

How to add and update data using SQL

How to query data and sort/filter it to find specific information

How real datasets (like football stats) can be used for analysis

It also gave me more confidence writing SQL by hand and understanding how relational databases work.

**Future Ideas**

Add data from other seasons to compare results

Create a separate table for players and managers

Build visual charts from the data using Python or Power BI

**Files**

premierleague_1819.sql → full SQL script to create and insert the data

**About Me**

I’m currently learning SQL and databases as part of my journey into tech.
I really enjoy working with data and using it to find patterns or insights.
This project was a great way to combine something I enjoy (football) with improving my technical skills.

**Shrish Umamaheswaran**
