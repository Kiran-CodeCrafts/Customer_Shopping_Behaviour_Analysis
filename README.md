# Customer_Shopping_Behaviour_Analysis

Customer Shopping Behavior Analysis

A  project that looks at 3,900 customer purchases to find out what makes people spend more, and how a business can use that to make better decisions.

What is this project about?
We had a dataset of shopping transactions. The goal was to clean the data, study it, run some SQL queries, build a dashboard, and find useful patterns — like which customers spend the most, which products are rated best, and what marketing ideas could increase sales.

About the Data
•	3,900 rows — one row per purchase
•	18 columns — things like age, gender, product type, amount spent, discount used, shipping type, subscription status, and review rating
•	37 missing values — only in the review rating column, so we filled them in using the median rating

Tools Used
•	Python (Pandas) — to load and clean the data
•	MySQL — to store the data and run SQL queries
•	Power BI — to build a visual dashboard


Workflow  

1.	Loaded the data into Python
2.	Checked the data — looked at columns, types, and basic stats
3.	Fixed missing values in the review rating column
4.	Created new features, like age groups and how often people buy
5.	Moved the cleaned data into MySQL
6.	Ran SQL queries and explored the data to find patterns
7.	Built a dashboard in Power BI to show the findings visually
8.	Wrote up the results in a powerpoint
   
What the Dashboard Shows
•	Who spends more — men or women
•	Which customers use discounts but still spend a lot
•	Which products get the best reviews
•	Whether express shipping customers spend more
•	How subscriptions affect spending and loyalty
•	How customers are grouped: new, returning, or loyal

What I Found:-
•	Gender: Women spend slightly more overall than men
•	Discounts: Some customers use discounts but are still big spenders — a good group to target with special offers
•	Best products: Blouses and dresses get the highest ratings, shirts are close behind
•	Shipping: Customers who choose express shipping spend about 12% more per order ($65 vs $58)
•	Subscriptions: Subscribers spend 68% more, bring in 45% of total revenue, and 78% of them come back to buy again
•	Customer groups: 50% are new customers, 35% are returning, and 15% are loyal repeat buyers

Suggestions:-
1.	Get more customers to subscribe — offer them exclusive perks
2.	Start a loyalty program to keep repeat customers coming back
3.	Target high spenders and express-shipping customers with special marketing
4.	Promote the best-rated products (blouses, dresses, shirts) more heavily
5.	Focus on turning new customers into returning ones, and returning ones into loyal ones


How to Run This Project

Follow the steps below to set up and run the project on your local machine.

Prerequisites

Make sure you have the following installed:

Python 3.10 or later
MySQL Server
Power BI Desktop

Step 1: Install the Required Python Libraries

Open a terminal or command prompt and install the required dependencies:

pip install pandas numpy sqlalchemy pymysql

Note: If your project uses mysql-connector-python instead of PyMySQL, install it using:

pip install mysql-connector-python

Step 2: Set Up the MySQL Database
Install and start the MySQL Server.
Create a new database.
Import the dataset into MySQL.
Update the database connection details in the config.py file with your MySQL credentials.

Example:

DB_HOST = "localhost"
DB_PORT = 3306
DB_NAME = "your_database_name"
DB_USER = "your_username"
DB_PASSWORD = "your_password"

Step 3: Run the Python Analysis Script

Execute the main Python script to clean, process, and analyze the data.
The script will:

Connect to the MySQL database.
Load the data.
Perform data cleaning and preprocessing.
Generate exploratory data analysis (EDA).
Calculate key business insights and KPIs.

