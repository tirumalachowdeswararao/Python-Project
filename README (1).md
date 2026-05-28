# Eazydiner-webscraping-and-analysis
## EasyDinner Restaurant Data Analysis – Python | EDA | Visualization

This project performs an end-to-end Exploratory Data Analysis (EDA) on the EasyDinner restaurant dataset to understand pricing patterns, ratings, locality trends, cuisine distribution, and discount behavior across restaurants in Hyderabad. The dataset was cleaned using regular expressions, transformed into analytical features, and explored using univariate, bivariate, and multivariate visualizations.

✅ Key Tasks Performed

- Cleaned and transformed raw restaurant data using pandas and regex.

- Extracted structured features such as:
  Name, Rating_Value, Price_For_Two, Price_Per_Person, Primary_Cuisine, Cuisine_Count, Max_Discount, Locality, City

- Removed duplicates, handled missing values, and standardized categorical attributes.

- Engineered analysis-ready columns including Price per Person, Max Discount, and Cuisine Count.

✅ Univariate Analysis

- Distribution of numeric variables: Price_For_Two, Rating_Value, Max_Discount, Cuisine_Count

- Count and frequency analysis for categorical variables: Primary_Cuisine, Locality, City

- Visualizations: Histogram, Boxplot, Countplot, KDE Plot

✅ Bivariate Analysis

- Numerical vs Numerical: Scatter plots for Price vs Rating, Rating vs Max_Discount

- Numerical vs Categorical: Boxplots and bar charts for Cuisine vs Price, Locality vs Rating

- Categorical vs Categorical: Crosstab heatmaps for Cuisine vs Locality

✅ Multivariate Analysis

- Bubble plots (scatter with hue + size) to visualize Price, Rating, Discount, Cuisine simultaneously.

- Heatmaps to analyze locality–cuisine pricing trends.

- Pairplots to examine interactions among multiple numeric features.

✅ Tools & Libraries

- Python, Pandas, NumPy

- Matplotlib, Seaborn

J- upyter Notebook / Google Colab

✅ Insights

- Multicuisine and North Indian restaurants dominate the dataset.

- Premium fine-dining areas like Jubilee Hills and Banjara Hills show higher pricing.

- Discounts tend to cluster around 10–25%, with limited impact on rating.

- Higher-priced restaurants generally trend towards higher ratings.

✅ Result

A fully cleaned, feature-engineered dataset along with comprehensive visualizations that highlight key patterns in restaurant pricing, customer ratings, cuisines, locality behavior, and discount strategies.
