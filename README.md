# California Housing Dataset for ML Pipeline Tutorial

## Overview
This dataset is specifically prepared for the "Building Your First ML Pipeline" tutorial on TheDataCareer.com.

## Files Included
- `california_housing_dataset.csv` - Complete dataset (20,640 rows)
- `california_housing_sample.csv` - Sample dataset (1,000 rows) for quick testing
- `data_dictionary.csv` - Feature descriptions and data types
- `README.md` - This file

## Dataset Description
The California housing dataset contains information about housing districts in California, derived from the 1990 U.S. census. This dataset is perfect for learning regression techniques and building ML pipelines.

**Target Variable**: Median house value in hundreds of thousands of dollars

## Features
### Original Features (from scikit-learn)
- **MedInc**: Median income in block group (tens of thousands of dollars)
- **HouseAge**: Median house age in block group (years)
- **AveRooms**: Average number of rooms per household
- **AveBedrms**: Average number of bedrooms per household
- **Population**: Block group population
- **AveOccup**: Average number of household members
- **Latitude**: Block group latitude
- **Longitude**: Block group longitude

### Engineered Features (for demonstration)
- **income_per_person**: Income per person (derived feature)
- **rooms_per_person**: Rooms per person (derived feature)
- **bedrooms_ratio**: Bedrooms to rooms ratio (derived feature)
- **income_category**: Income level category (Very Low, Low, Medium, High, Very High)
- **location_category**: Geographic location (Bay Area, Los Angeles, San Diego, Other)

## Usage
Perfect for:
- Learning data preprocessing techniques
- Feature engineering practice
- Regression model training
- ML pipeline development
- Model evaluation and comparison

## Tutorial
Follow the complete tutorial at: [TheDataCareer.com - ML Pipeline Guide](https://thedatacareer.com)

## Data Source
Original data from scikit-learn's California housing dataset, enhanced with additional features for educational purposes.

## License
This dataset is provided for educational purposes. Original data is public domain.
