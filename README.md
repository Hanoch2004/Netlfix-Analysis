# Netlfix-Analysis
Comprehensive analysis of Netflix's content catalog with advanced visualizations and growth forecasting


## Overview
This project provides a comprehensive analysis of Netflix's content catalog, examining trends, patterns, and characteristics of movies and TV shows available on the platform. The analysis includes data cleaning, exploratory analysis, advanced visualizations, and growth forecasting.

## Key Features
- Data cleaning and preprocessing pipeline
- Exploratory data analysis with key statistics
- Advanced visualizations (6-panel dashboard)
- Genre analysis using multi-label binarization
- Content longevity metrics
- Time series analysis and growth forecasting

## Key Findings
- **Content Distribution**: 69.6% Movies, 30.4% TV Shows
- **Peak Years**: Most content released in 2018, added to Netflix in 2019
- **Average Duration**: Movies (99.6 minutes), TV Shows (1.8 seasons)
- **Top Genres**: International Movies, Dramas, Comedies
- **Addition Patterns**: July sees the most content additions
- **Growth Forecast**: Projected content growth rate of -1.1% annually

## Technical Details
- **Languages**: Python
- **Libraries**: Pandas, NumPy, Matplotlib, Seaborn, WordCloud, Scikit-learn
- **Data**: Netflix catalog data (1925-2021)

## Usage
1. Clone the repository
2. Ensure all required libraries are installed
3. Run the Jupyter notebook or Python script
4. View generated visualizations in the `/output` folder

## File Structure

netflix-analysis/
├── data/
│ └── netflix.csv # Raw data file
├── output/
│ ├── netflix_advanced_dashboard.png # Main visualization
│ └── netflix_growth_forecast.png # Forecast visualization
├── netflix_analysis.ipynb # Jupyter notebook
└── README.md

## Requirements
- Python 3.6+
- pandas
- numpy
- matplotlib
- seaborn
- wordcloud
- scikit-learn

## Installation
```bash
pip install -r requirements.txt
