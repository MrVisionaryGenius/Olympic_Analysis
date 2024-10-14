# Olympic Analysis (120 Years of Data)

This repository contains an Olympic data analysis web application built using Streamlit and advanced Python libraries. The analysis covers 120 years of Olympic data (up to 2016) and includes features such as medal tally, country-wise analysis, and athlete performance.

## Features
- Medal Tally: View the overall medal tally, or filter by specific years and countries.
- Overall Analysis: Explore top statistics like number of editions, participating nations, and events over time.
- Country-wise Analysis: View a country's medal tally over the years and analyze its performance in different sports.
- Athlete-wise Analysis: Explore distribution of athletes by age and analyze performance by individual athletes.

## Data
The analysis is based on two datasets:

- athlete_events.csv: This file contains detailed information about each athlete's participation and achievements in the Olympics.
- noc_regions.csv: This file maps the National Olympic Committee (NOC) codes to the respective regions (countries).

## Setup Instructions
1. Clone the repository:
```python
git clone https://github.com/your-username/olympic-analysis.git
```
2. Install dependencies: Ensure you have Python 3.x installed. Then run:
```python
pip install -r requirements.txt
```
3. Run the app: Start the Streamlit application using the following command:
```python
streamlit run app.py
```
4. Explore the app: After running the app, a new tab in your browser will open, allowing you to explore the Olympic data and visualizations.

## Project Structure

📁 olympic-analysis/
- 📄 app.py               # Main Streamlit app for data visualization
- 📄 preprocessor.py      # Contains data preprocessing functions
- 📄 helper.py            # Contains functions for medal tally and analysis
- 📄 requirements.txt     # Python package dependencies
- 📁 csvs/                # Contains the datasets (athlete_events.csv and noc_regions.csv)

## Contributing
Feel free to fork this repository and submit pull requests. For major changes, please open an issue first to discuss what you would like to change.

## Live link: 
[Live Project](https://olympicanalysis-wp2hnge27sfr8awfhn8rt8.streamlit.app/)
