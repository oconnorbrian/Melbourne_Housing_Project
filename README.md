## Description  
This project analyzes historical housing data from Melbourne, Australia, to uncover long-term trends in property prices and the key factors that influence them. Using Python and popular data analysis libraries, the dataset was cleaned, transformed, and explored to gain insights into how residential property values have changed over time — and how features such as location, property type, and number of rooms relate to sale price. The analysis was part of a broader effort to develop practical, end-to-end data analytics skills with real-world datasets.

### Python Libraries: Pandas, NumPy, Seaborn, Matplotlib, Statsmodels, Folium

## Objectives  
* Investigate the rise in Melbourne housing prices over time  
* Identify which property types and suburbs command the highest prices  
* Understand the influence of features like room count and building area on sale price  
* Perform full-cycle data analysis, from raw data to actionable insights  
* Communicate findings using clear visualizations and summaries

## Data Analyst Skills Demonstrated  
* **Data Acquisition:** Loaded a real-world housing dataset from CSV format for analysis  
* **Data Cleaning & Preprocessing:**  
  - Handled missing and inconsistent data  
  - Removed invalid entries
  - Converted sale date strings to datetime format and extracted the year for trend analysis  
  - Renamed columns to correct typos for clarity and consistency  
  - Managed duplicates based on address and date to maintain data integrity  
* **Exploratory Data Analysis (EDA):**  
  - Explored distributions of key variables (price, rooms, land size, etc.)  
  - Grouped and aggregated data by year, suburb, and property type to find patterns  
  - Calculated statistical summaries (mean, median) to understand central tendencies  
* **Feature Engineering:**  
  - Extracted year and date components from sale dates  
  - Created new variables such as log-transformed prices for regression analysis  
  - Computed price differences and time differences between property resales  
* **Statistical Analysis:**  
  - Performed correlation analysis to quantify relationships between variables (e.g., price vs. distance to CBD, days between sales vs. profit)  
  - Conducted multiple linear regression using Statsmodels to model price as a function of key features  
  - Interpreted regression outputs including coefficients, and R-squared for insights on variable significance and model fit  
  - Applied log transformations to improve model assumptions and stabilize variance  
* **Data Visualization:**  
  - Built informative line plots, scatter plots, bar charts, and horizontal bar plots using Seaborn and Matplotlib  
  - Visualized geographic data interactively on maps using Folium with MarkerCluster for spatial insights  
  - Customized plot aesthetics including axis formatting, gridlines, and color coding for clarity and impact  
* **Insight Generation & Communication:**  
  - Identified long-term upward trends in Melbourne property prices  
  - Found that property type and suburb are strong indicators of price differences  
  - Highlighted correlations between distance to CBD and property price, and the influence of rooms on price through regression  
  - Provided actionable recommendations based on data, such as identifying affordable properties matching specific criteria  
  - Delivered findings in a structured, clear, and visually compelling format using both textual summaries and interactive elements
