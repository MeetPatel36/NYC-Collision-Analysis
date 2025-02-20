# New York City Collision Analysis

In this analysis, I examined New York City's open-source dataset on motor vehicle collisions. The aim of the analysis was to identify the street with the highest number of collisions, determine the most common causes of accidents, and identify the types of vehicles typically involved.

## Tools Used:

I utilized Python libraries like Pandas and NumPy to explore and clean the dataset. Additionally, I employed Matplotlib and Seaborn for visualization purposes.

## Data Cleaning Summary:

In the data cleaning process, I encountered numerous missing values primarily due to reports involving two or fewer vehicles. This resulted in incomplete information in the 'CONTRIBUTING FACTOR VEHICLE' and 'VEHICLE TYPE CODE' columns. To address this, I populated missing entries with 'Not Applicable.' 

I also removed any columns labeled 'Unspecified' in the 'CONTRIBUTING FACTOR VEHICLE' category, as they were irrelevant to our goal of analyzing accident causes. 

Furthermore, I addressed inconsistencies in the 'VEHICLE TYPE CODE' column, which contained many mismatched strings and incomplete entries. I focused on vehicle types with counts exceeding 500 and manually mapped and grouped them. For instance, I consolidated 'station wagon/sport utility vehicle' and 'sport utility/station wagon' into a single category labeled 'SUV.' 

These steps not only improved the dataset's quality but also made it more suitable for analysis.
