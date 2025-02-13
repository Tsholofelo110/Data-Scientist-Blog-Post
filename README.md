# Boston Airbnb Market Analysis

## Project Overview
This project analyzes Boston's Airbnb market to uncover insights about pricing patterns, guest satisfaction drivers, and market dynamics. Using data science techniques and the CRISP-DM methodology, we examine seasonal trends, neighborhood differences, and factors influencing property success.

## Motivation
The short-term rental market in Boston presents unique challenges and opportunities for both hosts and travelers. This analysis aims to:
- Help hosts optimize their pricing strategies
- Guide travelers in finding the best deals
- Understand what drives guest satisfaction
- Identify market patterns across different neighborhoods

## Data Sources
The analysis uses Airbnb data from Boston (2016-2017), including:
- Listings data (3,585 properties)
- Calendar data (1,308,890 records)
- Reviews data (68,275 reviews)

## Libraries Used
```python
pandas==1.5.3
numpy==1.23.5
matplotlib==3.7.1
seaborn==0.12.2
scikit-learn==1.2.2
```

## Repository Structure
```
boston-airbnb-analysis/
│
├── data/                      # Data files
│   ├── listings.csv          # Property listings data
│   ├── calendar.csv          # Availability and pricing data
│   └── reviews.csv           # User reviews data
│
├── notebooks/                 # Jupyter notebooks
│   ├── 01_data_cleaning.ipynb        # Data preparation
│   ├── 02_seasonal_analysis.ipynb    # Seasonal trends
│   ├── 03_satisfaction_analysis.ipynb # Guest satisfaction
│   └── 04_price_analysis.ipynb       # Price factors
│
├── src/                      # Source code
│   ├── data_preparation.py   # Data cleaning functions
│   ├── analysis.py           # Analysis functions
│   └── visualization.py      # Visualization functions
│
├── images/                   # Generated figures
├── requirements.txt          # Project dependencies
└── README.md                 # Project documentation
```

## Key Findings

### Seasonal Trends
- Peak pricing occurs in September-October
- Winter months show 20-30% lower prices
- Property availability varies significantly by season and neighborhood

### Guest Satisfaction
- Price is the strongest driver of review scores (0.68 importance)
- Property accommodations and amenities significantly impact satisfaction
- Most properties maintain high review scores (above 4.5/5)

### Price Factors
- Number of amenities is the top price influencer
- Room type (Private room) strongly affects pricing
- Premium neighborhoods (South Boston Waterfront, Back Bay) command higher prices
- Strong correlation between property size metrics and price

## Running the Analysis
1. Clone this repository
```bash
git clone https://github.com/username/boston-airbnb-analysis.git
```

2. Install required packages
```bash
pip install -r requirements.txt
```

3. Run the notebooks in order:
- First run data cleaning
- Then run individual analysis notebooks

## Blog Post
A detailed analysis and discussion can be found in this [Medium post]([link-to-medium-post](https://medium.com/@manamelatsholofelo2/bostons-airbnb-market-a-data-driven-guide-for-hosts-and-travelers-9133a85597ce)).



## Acknowledgements
- Data provided by Airbnb through Inside Airbnb
