# Pandas Practice

This repository contains my Pandas practice work using the Nigeria Sales Dataset.

I used this dataset to learn and practice:

* Reading CSV files
* Data cleaning
* Filtering rows and columns
* Using query()
* Working with loc and iloc
* Sorting data
* Finding counts and averages
* Basic data analysis with Pandas

Tools used:

* Python
* Pandas
* Google Colab

This repository will be updated regularly as I learn more Pandas concepts.

## Data Cleaning - Nigeria Sales Dataset

I worked on cleaning two important columns in this dataset — 
State and Product. The data had some messy values that needed 
to be fixed before analysis.

### What I found and fixed

**State Column**
Some rows had product names like Tablet, Keyboard, Laptop 
sitting inside the State column. I manually corrected those 
rows (101 to 107) and put the right state names back.

**Product Column**
Two rows had garbage values — one had `5578` and another had 
`4567!!` instead of a proper product name. I replaced both 
with `Others` since the real product was unknown.
Also filled a few NaN values in the Product column with `Others`.

### Files I created after cleaning
- `state_cleaned.csv`
- `Product_cleaned.csv`

### What I learned from this
Real datasets are never clean. Even a simple column like State 
can have wrong data sitting in it. Cleaning takes more time 
than actual analysis — but it is the most important step.



## Final Dataset Cleaning Summary

Additional cleaning tasks performed:

- Cleaned invalid values in the Sales Channel column
- Replaced invalid UUID entries with valid sales channel categories
- Handled missing values in the Order ID column
- Checked duplicate Order IDs
- Removed unnecessary columns
- Verified data consistency and data types

### Final Files
- Final.ipynb
- Final_nigeria_cleaned_dataset.csv
