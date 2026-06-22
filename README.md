# Zomato Restaurant Analysis – Global EDA

EDA on the Zomato dataset covering restaurants across 15 countries — analysing ratings, cuisines, pricing, and customer behaviour using Python.


## Dataset

- **zomato.csv** — restaurant names, locations, cuisines, ratings, votes, price range, delivery/booking info
- **Country-Code.xlsx** — maps country codes to country names for geographic analysis

  
## What I Did

**Data Cleaning**
- Removed duplicates and handled missing values
- Fixed inconsistent text formatting
- Converted columns to correct data types
  #
**Feature Engineering**
- Merged country names from the mapping file
- Extracted primary cuisine from multi-cuisine entries
- Categorised restaurants by price range and rating labels
  #
**Key Questions Explored**
- Which countries and cities have the most restaurants?
- Which cuisines dominate globally vs. regionally?
- Does price range affect customer ratings?
- How does online delivery availability impact votes and ratings?
  #
**Visualisations**
- Country-wise restaurant distribution
- Top cuisines globally
- Rating distribution across countries
- Price vs. rating and votes vs. rating comparisons
  

## Tech Stack

Python, Pandas, NumPy, Matplotlib, Seaborn, Jupyter Notebook


## How to Run

```bash
git clone https://github.com/Ayush28042005/ZomatoRestaurantAnalysis--Global-EDA.git
cd ZomatoRestaurantAnalysis--Global-EDA
pip install pandas numpy matplotlib seaborn openpyxl
jupyter notebook exploratory-data-analysis.ipynb
```

## Author

Ayush Saini
