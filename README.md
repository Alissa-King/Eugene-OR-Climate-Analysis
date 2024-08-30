# Climate Analysis Project for Eugene, Oregon

## Overview
This project analyzes historical climate data for Eugene, Oregon, and projects future temperature trends. It also explores the relationship between climate variables and agricultural production (using grass seed production as an example) in the Willamette Valley.

## Features
- Fetches climate data from NOAA for Eugene, Oregon (1970-2022)
- Processes and visualizes temperature and precipitation trends
- Projects temperature trends to 2050 using linear regression
- Analyzes the relationship between temperature and grass seed production
- Provides summary statistics and change rates for temperature and precipitation

## Requirements
- Python 3.7+
- pandas
- matplotlib
- seaborn
- scikit-learn
- requests
- numpy

## Installation
1. Clone this repository:
   ```
   git clone https://github.com/yourusername/climate-analysis-eugene.git
   cd climate-analysis-eugene
   ```
2. Install the required packages:
   ```
   pip install -r requirements.txt
   ```

## Usage
Run the main script:
```
python climate_analysis.py
```

This will generate several visualizations:
1. Annual Average Temperature trend (1970-2022)
2. Annual Precipitation trend (1970-2022)
3. Temperature Projection (1970-2050)
4. Relationship between Temperature and Grass Seed Production

The script will also print summary statistics and estimated change rates for temperature and precipitation.

## Data Sources
- Climate data: NOAA Daily Summaries dataset
- Agricultural data: Placeholder random data (in a real scenario, this would be fetched from USDA or Oregon state sources)

## Notes
- All temperatures are in Fahrenheit (°F)
- Precipitation is measured in millimeters (mm)
- Grass seed production is measured in pounds

## Future Improvements
- Incorporate real agricultural data from reliable sources
- Add more sophisticated climate projection models
- Expand the analysis to include other climate variables and agricultural products

## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Contributors
- Alissa King

## Acknowledgments
- NOAA for providing access to climate data
- The scientific community for ongoing research in climate change and its impacts on agriculture
