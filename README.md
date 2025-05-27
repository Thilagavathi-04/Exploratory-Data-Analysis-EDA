# Airplane Crashes Dataset - Exploratory Data Analysis (EDA)

# Project Title:

Exploratory Data Analysis on the Airplane Crashes Dataset

# Objective:

The objective of this project is to perform a comprehensive exploratory data analysis (EDA) on the "Airplane Crashes Since 1908" dataset to uncover meaningful insights, detect patterns and trends, visualize the distribution of data, and identify potential anomalies such as outliers.

# Dataset:

**Name:** Airplane Crashes Since 1908

**Source:** Kaggle - Airplane Crashes Dataset

**File Used:** airplane_crash dataset.csv

**Tools & Libraries Used:**

-Python (Jupyter Notebook)

-pandas – Data manipulation

-numpy – Numerical operations

-matplotlib, seaborn – Static data visualization

-plotly – Interactive data visualization

# Project Structure:

── airplane_crash dataset.csv

── airplane_crash_eda.ipynb

── processed_airplane_crashes.csv 

── README.md

# Key Steps Performed:

**1. Data Acquisition & Exploration**

Loaded the dataset using pandas.

Displayed top rows and info.

Inspected column types and missing values.

**2. Data Cleaning**

Converted Date to datetime format using errors='coerce'.

Extracted Year from Date.

Handled missing values appropriately.

**3. Summary Statistics**

Computed statistics like mean, median, standard deviation, min, and max for numeric fields.

**4. Visual Explorations**

a. Histograms

      Distribution of Fatalities

b. Boxplots

      Boxplot of Fatalities

      Boxplot of Aircraft Age (if column exists)

c. Correlation Heatmap

       Correlation matrix among numeric variables using heatmap.

d. Temporal Trends

       Line chart showing crashes per year.

e. Pair Plot

       sns.pairplot() for Fatalities, Aboard, and Ground.

f. Interactive Plot

       Plotly scatter plot of Aircraft Age vs. Fatalities.

**5. Outlier Detection**

       Used boxplots to visually detect outliers in numeric features like Fatalities and Aircraft Age.



# Conclusion:

This EDA project provides valuable insights into airplane crashes over time. The dataset has been cleaned, explored, and visualized thoroughly to identify key patterns, trends, and anomalies. This work lays the foundation for more complex modeling tasks or domain-specific investigations.



