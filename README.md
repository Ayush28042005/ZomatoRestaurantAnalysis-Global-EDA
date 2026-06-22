**Zomato Restaurants – Exploratory Data Analysis**

Exploratory data analysis on the Zomato dataset covering restaurants across 15 countries. The goal was to dig into real-world messy data and pull out meaningful patterns around ratings, cuisines, pricing, and customer behaviour.
---

Dataset
Two files were used:
1) zomato.csv — main dataset with restaurant names, locations, cuisines, ratings, votes, price range, and online delivery/table booking info
2) Country-Code.xlsx — maps country codes to country names, merged in to enable country-level analysis
---

What I Did
Data Cleaning
Removed duplicate entries
Handled missing values in cuisine and rating columns
Fixed inconsistent text formatting
Converted columns to appropriate data types
Feature Engineering
Merged country names from the code mapping file
Extracted primary cuisine from multi-cuisine entries
Categorised restaurants by price range and rating colour labels


Analysis & Insights
Explored questions like:
Which countries and cities have the highest restaurant density?
Which cuisines are most popular globally vs. regionally?
Does price range correlate with customer ratings?
How does online delivery availability affect ratings and votes?
Which restaurants are outliers — unusually high or low rated?


Visualisations:
Country-wise restaurant distribution (pie chart)
Top cuisines globally (bar plot)
Rating distribution across countries
Price vs. rating comparison
Votes vs. rating scatter plot
---

Tech Stack
Python, Pandas, NumPy, Matplotlib, Seaborn, Jupyter Notebook
---

How to Run
```bash
git clone https://github.com/Ayush28042005/ZomatoRestaurantAnalysis--Global-EDA.git
cd ZomatoRestaurantAnalysis--Global-EDA
pip install pandas numpy matplotlib seaborn openpyxl
jupyter notebook exploratory-data-analysis.ipynb
```

---
Author
Ayush Saini 
