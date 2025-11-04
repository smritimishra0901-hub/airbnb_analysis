# 🏙️ Airbnb Neighbourhood Correlation Analysis

## 📊 Overview

This project performs exploratory data analysis (EDA) on Airbnb neighbourhood data for New York City.
It focuses on identifying correlations between various listing and review-related attributes — such as prices, ratings, reviews, and accommodation counts — across different boroughs.

## 🧠 Objectives

* Explore the dataset using descriptive statistics.
* Visualize feature correlations across all neighbourhoods.
* Generate correlation heatmaps for individual boroughs (e.g., Bronx, Manhattan, Queens).
* Automate correlation visualization through a reusable function.

## 🧰 Tools and Libraries

* **Python 3.x**
* **pandas** — data manipulation and cleaning
* **seaborn** — heatmap and data visualization
* **matplotlib** — plotting utilities

## 📂 Data

The dataset used:
`Updated Neighbourhoods.xlsx`
Contains columns like:

* `neighbourhood_group_cleansed`
* `NeighbourhoodArea`
* `Listings`
* `minp`, `maxp`, `avgp`
* `minscores`, `maxscores`, `avgscores`
* `rev` (reviews)
* `acc` (accommodation count)

## ⚙️ How It Works

1. Load and clean the dataset using pandas.
2. Drop non-numeric columns to compute correlations.
3. Generate overall correlation heatmaps.
4. Filter and visualize borough-specific correlations.
5. Use the `correl(name)` function to display correlation heatmaps for any neighbourhood group.

Example:

```python
correl('Bronx')
correl('Manhattan')
```

## 📈 Output

* Correlation heatmaps showing relationships between numerical variables.
* Insights into which metrics (price, reviews, scores) are related or independent across boroughs.

## 📦 File Structure

```
airbnb_analysis.ipynb        # Main Jupyter Notebook
Updated Neighbourhoods.xlsx   # Input dataset
README.md                     # Project documentation
```

## ✨ Author

**Smriti**
Exploring data-driven insights through visualization and analysis.
