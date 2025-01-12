# Chemicals-in-Cosmetics

Description of the Data: The data source is from the California Safe Cosmetics Program, which operates under the California Department of Public Health. This data set provides hazardous chemicals in cosmetic products sold in California. Data includes details about chemicals that are listed as known or suspected to cause cancer, birth defects, or reproductive harm and have been reported to the state as required by the California Safe Cosmetics Act (2005). Under the law, manufacturers, packers, or distributors with annual sales exceeding $1 million are required to report such products to the CSCP.

Python Packages Used: pandas, numpy, matplotlib, seaborn, plotly, wordcloud

File Structure: chemicals-in-cosmetics.csv - Main dataset, chemicalsincosmetics-dd-subcategories.xlsx - Additional categories dataset, Chemicals-in-Cosmetics.ipynb Google Colab for the project, README.md - This file, providing project details.

Data Loading and Exploration: Loaded two datasets: the first one containing hazardous chemicals' details and the second one with categories, Viewed data structure, missing values identified.

Data Cleaning and Transformation: Filled missing values with appropriate placeholder or statistical measurements, Merging the two data sets for completeness of chemicals in various categories, Removed rows with duplicate data for cleanliness of the data.

Statistical Insights: Summarizing statistics for numeric columns, Identifying the top 10 most common hazardous chemicals used and the top companies with highest usage.

Data Visualization:
Created visualizations to show trend and distributions: Line plot: Trend in reported hazardous chemicals through the years, Bar plots: Distribution across categories, top 10 chemicals, Pie chart: top companies contributing in hazardous chemical usage, Heatmap: Chemical usage by categories and companies, Scatter plot: Usage of chemicals reported over time by a company, Word cloud: words of most frequently reported hazardous chemicals

Key Insights:
The distribution of hazardous chemicals varies significantly across categories.
Top Company contribute heavily to the presence of hazardous chemicals. The top Company is L'Oreal USA.
The most common hazardous chemicals include Titanium dioxide, Silica, crystalline (airborne particles of respirable size), Retinol/retinyl esters, when in daily dosages in excess of 10,000 IU, or 3,000 retinol equivalents.
