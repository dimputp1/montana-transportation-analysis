# Montana Cities Transportation and Walkability Analysis

This project analyzes transportation emissions and walkability indices for cities in Montana, providing insights into sustainable transportation patterns.

## Overview

The analysis explores the relationship between vehicle usage, greenhouse gas emissions, and walkability in Montana cities. Using data from the EPA and other sources, we identify cities that may benefit from improved walkability infrastructure to reduce emissions.

## Key Findings

- **Data Scope**: Analysis of 129 Montana cities
- **Emissions Range**: Combined GHG emissions per capita range from 2.05 to 47.90 metric tons CO2 equivalent
- **Walkability**: National Walkability Index averages 7.61 across Montana cities
- **High Priority Cities**: 7 cities identified with high emissions and low walkability that could benefit from transportation improvements

## Files

- `montana_analysis.ipynb` - Complete Jupyter notebook with data loading, cleaning, analysis, and visualizations
- `cleaned_full_city_data.csv` - Processed city-level data
- `processed_city_data.csv` - Final processed dataset
- `figures/` - Generated plots and interactive visualizations
- `NotesFor603Team.docx` - Original project notes

## Data Sources

- City-level transportation and emissions data
- Walkability indices from EPA Smart Location Database
- Census block group mappings

## Analysis Includes

1. **Data Cleaning**: Handling missing values and invalid data
2. **Exploratory Data Analysis**: Statistical summaries and distributions
3. **Correlation Analysis**: Relationships between emissions and walkability
4. **Visualizations**:
   - Distribution plots
   - Correlation heatmaps
   - Scatter plots
   - Interactive Plotly charts
5. **City Rankings**: Top emitters and cities needing improvement

## How to Run

### Option 1: Google Colab
1. Upload `montana_analysis.ipynb` to Google Colab
2. Upload the data files (`cleaned_full_city_data.csv`)
3. Run all cells (dependencies are pre-installed or can be installed)

### Option 2: Local Environment
1. Install Python 3.7+
2. Install required packages: `pip install pandas numpy matplotlib seaborn plotly`
3. Run the Jupyter notebook

## Results

The analysis identifies specific Montana cities where investments in walkability could significantly reduce transportation emissions. Interactive visualizations allow exploration of the data relationships.

## Contributors

Montana Analysis Team

## License

This project is for educational and research purposes.