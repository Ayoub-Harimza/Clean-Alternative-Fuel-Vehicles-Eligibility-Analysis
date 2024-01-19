# About
 The goals of this analysis is to study Clean Alternative Fuel Vehicles Eligibility of E-vehicles registered in Washington State

# The used Dataset 
  [Electric Vehicle Population Data(Link of the website)](https://catalog.data.gov/dataset/electric-vehicle-population-data)
  
  [Electric Vehicle Population Data(The version used, last updated date:December 16, 2023)](https://drive.google.com/drive/folders/1i9nF2r2UxyUmlOk3pwUpcZOrgERtnl7b?usp=drive_link)


# Exploratory Data Analysis

In this Exploratory Data Analysis (EDA) section, the following actions were performed using Python with pandas, seaborn, and matplotlib:

1. Loaded the dataset (`Electric_Vehicle_Population_Data.csv`) into a pandas DataFrame.
2. Displayed the first few rows of the dataset using `df.head()` to get an initial glimpse.
3. Checked the basic information about the dataset using `df.info()`.
4. Explored the number of unique values in each column using `df.nunique()`.
5. Dropped columns deemed unimportant for the analysis.
6. Checked the shape of the DataFrame using `df.shape` to understand its dimensions.
7. Investigated and handled missing values using `df.isna().sum()` and subsequently removed rows with missing values from the DataFrame.

This EDA serves as the preliminary steps to understand the structure, content, and quality of the dataset before diving into further analysis and visualization.

# Data Visualization with Tableau
The data was visualized using Tableau. The interactive version of the dashboard can be found on [Tableau's website](https://public.tableau.com/views/Book2_17052462280990/Dashboard1?:language=en-US&:display_count=n&:origin=viz_share_link)
 or in the [resources](https://github.com/Ayoub-Harimza/Clean-Alternative-Fuel-Vehicles-Eligibility-Analysis/tree/main/Tableau%20visualizations).

I'ts clearly observed that out of the electric vehicles registered in Washington state, 39.46% (64,323 vehicles) meet the criteria for Clean Alternative Fuel Vehicles. Within this category, 73.27% are Battery Electric, while the remaining 26.73% are Plug-in Hybrid Electric. Conversely, among the Non-eligible vehicles, a significant 99.95% are Plug-in Hybrid, with only a minimal 0.05% being Battery Electric.




![Image](https://github.com/Ayoub-Harimza/Clean-Alternative-Fuel-Vehicles-Eligibility-Analysis/blob/main/Tableau%20visualization/DASHBOARD.PNG)

## Contact

Feel free to reach out if you have any questions or would like to discuss this project further:

- **Email:** Ayoubharimza21@gmail.com
- **LinkedIn:** [Ayoub Harimza](https://www.linkedin.com/in/ayoub-harimza-4926a22a7/)

