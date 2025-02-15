# **Uber Data Analytics Project**

In this project, we explored a dataset containing Uber ride information to uncover insights and answer key business questions. The analysis was performed using Python libraries such as Pandas, Seaborn, and Matplotlib for data manipulation and visualization.

## **Objectives:**
The main objectives of the project were to analyze patterns in Uber ride data, focusing on the following key questions:

### **Key Questions:**

- **In which category do people book the most Uber rides?**
  ![image](https://github.com/user-attachments/assets/328b6a5e-5881-483f-815b-55002656c4ac)


- **For which purpose do people book Uber rides the most?**
  ![image](https://github.com/user-attachments/assets/0140a342-c56a-433b-b136-878f2b54c0ae)


- **At what time do people book cabs the most from Uber?**
  ![image](https://github.com/user-attachments/assets/e458a4bd-89ae-419f-955e-a822307d1c67)


- **In which months do people book Uber rides less frequently?**
  ![image](https://github.com/user-attachments/assets/7e971f7a-9bd8-408a-91d0-48f67ff87968)


- **On which days of the week do people book Uber rides the most?**
  ![image](https://github.com/user-attachments/assets/3e311d9b-d0b0-4695-bf4d-fa4f94ccc160)


- **How many miles do people usually book a cab for through Uber?**
  ![image](https://github.com/user-attachments/assets/65223d10-eaac-4212-91e9-369e0f5c61de)


## **Data Cleaning Process:**

Before starting the analysis, the following steps were carried out to ensure the data was clean and ready for use:

- **Handling Missing Values:** Missing values were identified in certain columns and handled by either filling with appropriate values or removing rows where necessary. For example, missing values in the `MILES` column were imputed using the column's median value.
  
- **Data Type Conversion:** Columns like `START_DATE` and `MILES` were converted to the appropriate data types (e.g., datetime for dates, float for miles) to facilitate proper analysis.

- **New Columns Creation:** New columns were created for more detailed analysis:
  - `Month` was extracted from the `START_DATE` column to analyze monthly trends.
  - `Day` of the week was extracted from the `START_DATE` column to investigate ride booking patterns by day.
  
- **Fixing Inconsistent Data:** Some categorical variables had inconsistent or misspelled entries, which were corrected by standardizing the values (e.g., "Jan" and "January" were unified).

## **Tools Used:**

- **Pandas:** For data cleaning, handling missing values, extracting new columns, and performing data transformations.
  
- **Matplotlib & Seaborn:** Used for visualizing the distribution of Uber ride data. Key visualizations included bar plots, histograms, and line graphs for better understanding of trends.

## **Conclusion:**

The analysis provided actionable insights into ride booking patterns, which can help Uber optimize pricing, resource allocation, and marketing strategies based on the distribution of ride distances, peak demand days, and seasonal trends.

