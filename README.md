# Play-Store-Data-Analytics-
📌 Google Play Store Data Analytics - Python 🏆
📖 Project Description
This project is part of my Nullclass Internship Assignment, where I analyzed Google Play Store data to gain insights into app ratings, reviews, pricing, and user engagement. The project includes data cleaning, feature engineering, exploratory data analysis (EDA), and visualizations to extract meaningful patterns.

📂 Dataset Information
Source: Provided by Nullclass

File: Play Store Data.csv

Features Included:

App Name

Category

Rating

Reviews

Size

Installs

Type (Free/Paid)

Price

Content Rating

Genres

Last Updated

Current Version

Android Version

🚀 Features & Steps
🔹 Step 1: Load & Explore Data
✔ Load dataset using Pandas
✔ Check for missing values
✔ Handle incorrect data types

🔹 Step 2: Data Cleaning & Preprocessing
✔ Remove duplicate entries
✔ Handle missing values (drop/fill)
✔ Convert string-based numerical values (e.g., "3.0M" → 3000000)
✔ Convert price column (e.g., "$4.99" → 4.99)
✔ Convert installs to integer


🔹 Step 3: Exploratory Data Analysis (EDA)
✔ Find top categories based on number of apps
✔ Analyze the distribution of ratings
✔ Find correlation between reviews & ratings

🔹 Step 4: Data Visualization
✔ Top-rated app categories (Bar Chart)
✔ Number of Free vs. Paid apps (Pie Chart)
✔ Correlation between Installs & Ratings (Scatter Plot)
✔ Most installed app categories (Bar Chart)

🔹 Step 5: Time-Based Graph Visibility (3 PM - 5 PM Restriction)
✔ Implement Python datetime logic to show/hide graphs dynamically based on time

🔹 Step 6: Final Report & Documentation
✔ Summary of findings
✔ Conclusion and insights

📊 Technologies Used
Programming Language: Python 🐍
Libraries: Pandas, NumPy, Matplotlib, Seaborn, Plotly
#Project Structure
📂 Google_Play_Store_Analytics
│── 📄 Play Store Data.csv          # Dataset  
│── 📄 data_cleaning.py             # Data Cleaning Script  
│── 📄 analysis.ipynb               # Jupyter Notebook with EDA  
│── 📄 visualizations.py            # Visualization Code  
│── 📄 report.pdf                   # Final Report  
│── 📄 README.md                    # Project Documentation  


