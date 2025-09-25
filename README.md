# Hotel Bookings Analysis Project

This project analyzes hotel booking data to identify trends, patterns, and provide business insights.

## Project Structure

- `01_Data_Preparation.ipynb` - Data loading, cleaning, and feature engineering
- `02_Exploratory_Analysis.ipynb` - Exploratory data analysis and visualizations
- `03_Advanced_Analysis.ipynb` - Advanced analysis including interactive visualizations and risk scoring
- `Hotel_bookings_final.csv` - Raw dataset
- `requirements.txt` - Python package dependencies

## Setup Instructions

1. **Create a virtual environment:**
   ```bash
   python -m venv venv
   ```

2. **Activate the virtual environment:**
   - On Windows: `venv\Scripts\activate`
   - On macOS/Linux: `source venv/bin/activate`

3. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

4. **Start Jupyter Notebook:**
   ```bash
   jupyter notebook
   ```

## Execution Steps

Run the notebooks in the following order:

1. **01_Data_Preparation.ipynb**
   - Loads the raw data
   - Cleans missing values and duplicates
   - Creates new features (length_of_stay, is_cancelled, avg_daily_rate)
   - Saves cleaned data as `hotel_bookings_cleaned.csv`

2. **02_Exploratory_Analysis.ipynb**
   - Loads the cleaned data
   - Analyzes booking patterns by channel, room type, and star rating
   - Examines cancellation behavior
   - Shows seasonal and temporal trends

3. **03_Advanced_Analysis.ipynb**
   - Interactive revenue treemap visualization
   - Cancellation risk scoring model
   - High-value guest profiling
   - Advanced business insights

## Key Outputs

- Cleaned dataset: `hotel_bookings_cleaned.csv`
- Multiple visualizations and charts
- Business insights and recommendations
- Interactive Plotly visualizations

## Requirements

- Python 3.7+
- Jupyter Notebook
- See `requirements.txt` for complete package list
