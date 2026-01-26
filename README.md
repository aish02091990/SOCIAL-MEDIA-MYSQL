# SOCIAL-MEDIA-MYSQL
SOCIAL MEDIA MYSQL USE EMPLOYEES
Social Media Analytics using MySQL

Project Overview
This project performs end-to-end social media analytics using MySQL.
The goal is to analyze user engagement, content virality, activity trends, follower growth,
and hashtag popularity using real-world SQL queries.
The project simulates how platforms like Instagram, Twitter (X), or Facebook analyze
large volumes of social data to drive insights.

Objectives
• Identify top influencers based on engagement
• Detect viral posts with unusually high interaction
• Analyze user activity patterns over time
• Measure follower growth trends
• Discover trending hashtags

Technologies Used
• Database: MySQL
• Concepts:
o Joins
o Aggregation (COUNT, AVG)
o Subqueries
o GROUP BY, HAVING
o Date functions (CURDATE, INTERVAL, WEEK)

Database Schema
Tables Included
• users – Stores user profile information
• posts – Stores user posts
• likes – Stores likes on posts
• comments – Stores comments on posts
• followers – Stores follower relationships
• hashtags – Stores hashtag details
• post_hashtags – Mapping between posts and hashtags

Entity Relationship (ER) Summary
• One user can create many posts
• One post can have many likes, comments, and hashtags
• Users can follow other users
• Hashtags can be used in multiple posts

Key Analytics Queries
Top Influencers
Identifies users with the highest total engagement (likes + comments).
Business Use: Influencer ranking & creator monetization

Virality Report
Finds posts with engagement higher than average, marking them as viral.
Business Use: Viral content detection & promotion strategies

User Activity Timeline
• Daily posting trends
• Weekly posting trends
Business Use: Optimal posting schedule analysis

Follower Growth Analysis
Identifies users who gained the most followers in the last 30 days.
Business Use: Growth tracking & popularity metrics

Trending Hashtags
Finds most used hashtags in the last 30 days.
Business Use: Trend discovery & hashtag recommendation

Sample Insights Generated
• Top creators based on engagement
• High-impact viral posts
• Peak posting days and weeks
• Fastest growing user accounts
• Most popular hashtags

Skills Demonstrated
• Advanced SQL querying
• Data aggregation & analytics
• Real-world business problem solving
• Time-based data analysis
• Database design understanding

📁Project Structure
social-media-analytics/
│
├── schema.sql # Database schema
├── queries.sql # Analytics queries
├── README.md # Project documentation

How to Run the Project
1. Create a MySQL database
2. Execute schema.sql to create tables
3. Insert sample data (optional)
4. Run queries from queries.sql
5. Analyze results

Future Enhancements
• Add indexes for performance optimization

• Create views for dashboards
• Integrate with Power BI / Tableau
• Add sentiment analysis using text data

Database Schema
Tables Included
• users – Stores user profile information
• posts – Stores user posts
• likes – Stores likes on posts
• comments – Stores comments on posts
• followers – Stores follower relationships
• hashtags – Stores hashtag details
• post_hashtags – Mapping between posts and hashtags

Entity Relationship (ER) Summary
• One user can create many posts
• One post can have many likes, comments, and hashtags
• Users can follow other users
• Hashtags can be used in multiple posts

Skills Demonstrated
• Advanced SQL querying
• Data aggregation & analytics

• Real-world business problem solving
• Time-based data analysis
• Database design understanding

How to Run the Project
1. Create a MySQL database
2. Execute schema.sql to create tables
3. Insert sample data (optional)
4. Run queries from queries.sql
5. Analyze results

Future Enhancements:
• Add indexes for performance optimization
• Create views for dashboards
• Integrate with Power BI / Tableau
• Add sentiment analysis using text data

Follower Growth Analysis
Identifies users who gained the most followers in the last 30 days.
Business Use: Growth tracking & popularity metrics
Trending Hashtags
Finds most used hashtags in the last 30 days.
Business Use: Trend discovery & hashtag recommendation

Sample Insights Generated
• Top creators based on engagement
• High-impact viral posts
• Peak posting days and weeks
• Fastest growing user accounts
• Most popular hashtags

Skills Demonstrated
• Advanced SQL querying
• Data aggregation & analytics
• Real-world business problem solving
• Time-based data analysis
• Database design understanding
How to Run the Project
6. Create a MySQL database
7. Execute schema.sql to create tables
8. Insert sample data (optional)
9. Run queries from queries.sql
10. Analyze results

Future Enhancements
• Add indexes for performance optimization
• Create views for dashboards
• Integrate with Power BI / Tableau

• Add sentiment analysis using text data

Project Structure
social-media-analytics/
├── schema.sql # Database schema
├── queries.sql # Analytics queries
├── README.md # Project documentation

Conclusion
This project demonstrates how MySQL can be used to power real-world social media
analytics, enabling data-driven decisions and actionable insights.

• Add indexes for performance optimization
• Create views for dashboards
• Integrate with Power BI / Tableau
• Add sentiment analysis using text data
