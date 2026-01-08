# Exploratory Data Analysis of Global GDP Indicators

An exploratory data analysis project examining global economic patterns using World Bank and UN data, completed as part of the **Exploratory Data Analysis and Visualization** course (DLBDSEDAV01) at IU International University of Applied Sciences.

## Overview

This project applies EDA techniques to analyze economic indicators across 181 countries, including GDP, GDP growth, population, GDP per capita, and world GDP share. The analysis reveals patterns of global economic concentration, distribution characteristics, and relationships between variables.

## Dataset

**Global GDP** from Kaggle  
Source: [Kaggle Dataset](https://www.kaggle.com/datasets/asadullahcreative/global-gdp-explorer-2024-world-bank-un-data)

- 181 countries
- 7 economic variables
- Cross-sectional data (2023)

## Key Visualizations

- **Distribution Analysis**: Histograms, box plots, violin plots
- **Correlation Analysis**: Heatmaps, scatter plots, correlograms
- **Geographic Maps**: Choropleth maps of GDP per capita and growth rates
- **Concentration Analysis**: Pareto charts, treemaps
- **Outlier Detection**: IQR-based identification

## Viewing the Notebook

Due to file size, the notebook may not render directly on GitHub.  
**View via nbviewer**: [Open Notebook](https://nbviewer.org/github/santi753/IU_Exploratory_Data_Analysis_and_Visualization/blob/main/Global_GDP_EDA_Notebook.ipynb)

## Technologies

- Python 3
- Pandas, NumPy
- Matplotlib, Seaborn
- Plotly (interactive visualizations)
- Geopandas (geographic mapping)

## Key Findings

- Top 4 economies account for 50% of world GDP
- Top 20 economies account for 80% of world GDP
- Strong correlation between log(GDP) and log(Population): r = 0.78
- No linear correlation between GDP growth and GDP per capita: r ≈ 0

## Author

**Pedro Santiago Mari Bitar**  
IU International University of Applied Sciences

## License

This project is for educational purposes as part of academic coursework.