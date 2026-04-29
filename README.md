# Data Analysis using Python: 
                   This repository contains various data analysis projects performed using Python, specifically focusing on exploratory data analysis (EDA), data cleaning, and visualization.

# Projects Included:
             Diwali Sales Analysis: An analysis of consumer behavior and sales trends during the Diwali festival to identify key customer demographics and purchasing patterns.
# Key Insights:
* Identified the most profitable product categories.
* Analyzed the impact of age groups and gender on total sales volume.
             
Financial Market Uncertainty:
# Environment Setup & Data Loading:
             Library Imports: You have imported the essential Python libraries for data science: pandas for data manipulation, numpy for numerical operations, and matplotlib and seaborn for creating visualizations.
            Dataset Loading: The file loads a large dataset containing **12,000 entries** and **30 different columns** related to financial metrics.
# Exploratory Data Analysis (EDA):
             Data Inspection: You used df.head(5) to view the first few rows of the data, which includes features like Open_Price, Close_Price, Trading_Volume, and sentiment scores .
# Data Cleaning & Transformation:
             Dropping Columns: You removed the Decision and Holdings columns from the dataset to focus on the research variables.
             Handling Nulls: You verified that there are **zero null values** across all remaining 28 columns using pd.isnull(df).sum().
             Type Conversion: You changed the data type of the Drawdown column from a decimal (float) to a whole number (integer).
             Renaming: Although not shown in full, there is evidence of renaming columns (e.g., Cash_Available being referred to as Moolah_Touse in later outputs).
# Data Visualization:
             Custom Graphics: The notebook includes code to generate a wide bar plot using Seaborn to analyze GDP_Growth over time. You specifically set the figure size to (18, 6) and rotated the x-axis labels to 45 degrees to prevent the year labels from overlapping.
This notebook appears to be the foundation for your research into how financial market factors like the VIX_Index, Inflation_Rate, and News_Sentiment_Score contribute to market uncertainty.
  # Tools & Technologies Used:
        Languages: Python (Pandas, NumPy)
        Visualization: Matplotlib, Seaborn
        Environment: Jupyter Notebook

**Author:** Hira Ghazan  
*Currently pursuing research in Finance.
