# Wine Reviews Analysis

Exploratory data analysis of ~130,000 wine reviews using Python and Pandas.

## Dataset
Wine Reviews dataset from Kaggle (Wine Enthusiast magazine reviews).
- 129,971 rows and 13 columns
- Columns include country, points, price, province, variety, winery, taster name, and the review text

## Questions I Asked
1. Which columns have missing values, and how many?
2. Which 10 countries have the most reviews?
3. Which country has the highest average points?
4. Which wine is the best bargain (points per price)?
5. What are the 5 cheapest wines with 90+ points?

## Key Findings
- **Missing data:** `price` is missing in 8,996 reviews (about 7%), while `region_2` is missing in 79,460 (about 61%). Price is usable for analysis after dropping or filling those rows, but `region_2` is too sparse to rely on.
- **Coverage is heavily skewed:** the US has 54,504 reviews (about 42% of the dataset). The US, France and Italy together make up about 74% of all reviews, so conclusions about smaller countries rest on far less data.
- **Best bargain:** by points-to-price ratio, *Bandit NV Merlot (California)* ranks first. This ratio favors very cheap wines, so it is a rough measure of value, not quality.
- **Good wine does not have to be expensive:** the five cheapest wines rated 90+ points cost only $7-$8 each, for example *Herdade dos Machados 2012 Toutalga Red* from Portugal (91 points, $7).
- **Average points by country:** (fill in from your output: which country is first, and its average points)

## Tools
Python, Pandas, Matplotlib. Built in a Kaggle notebook.

## Notebook
(paste your Kaggle notebook link here)
