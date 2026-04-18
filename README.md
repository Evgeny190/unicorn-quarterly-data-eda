# Unicorns Quarterly Data EDA

This project explores a dataset of unicorn companies to identify patterns in when companies were founded, when they reached unicorn status, and how long that process took. The analysis focuses on structuring the data with Python and using visualizations to examine trends over time.

## Project overview

The notebook analyzes unicorn company data by:

- inspecting the structure and quality of the dataset
- converting date columns into datetime format
- creating new time-based features such as month, week, and quarter joined
- calculating the number of years it took companies to become unicorns
- comparing trends across weeks, months, quarters, and founding years
- visualizing company counts and valuation-related patterns

## Dataset

The notebook uses a dataset of unicorn companies containing information such as:

- company name
- year founded
- date joined
- valuation

## Tools used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Key analysis steps

### 1. Data loading and inspection
The dataset is loaded into a pandas DataFrame and reviewed using methods such as `head()`, `shape`, and duplicate checks.

### 2. Data preparation
The `Date Joined` column is converted to datetime format, and new columns are created to support time-based analysis:
- `Month Joined`
- `Years To Joined`
- `Week Joined`
- `Quarter Joined`

### 3. Trend analysis
The notebook groups and summarizes the data to explore:
- how many companies were founded each year
- how many companies joined unicorn status by week in 2021
- average valuation trends by quarter in 2020 and 2021
- how long it took companies to become unicorns depending on month joined and year founded

### 4. Visualization
Several charts are used to communicate findings, including:
- histogram of year founded
- boxplot of years to become a unicorn by month joined
- bar chart of years to become a unicorn by year founded
- bar chart of companies joining per week in 2021
- bar chart comparing quarterly patterns across years

## Key findings

Some of the main observations from the analysis include:

- The dataset contains over one thousand unicorn companies.
- 2015 had the highest number of companies founded in this dataset.
- Many companies that became unicorns in 2021 were founded in recent years.
- Structuring the data by week, month, quarter, and year makes it easier to identify temporal trends.
- Visualizations highlight how the journey to unicorn status differs depending on when a company was founded or joined.

## Files

- `Unicorns-quarterly-data-eda.ipynb` — main notebook containing the full analysis
- `Unicorn_Companies.csv` — source dataset used in the notebook

## How to run

1. Clone this repository
2. Open the notebook in Jupyter Notebook or JupyterLab
3. Make sure the dataset file is in the same folder as the notebook
4. Run the cells in order

## Project goal

The goal of this project is to demonstrate practical exploratory data analysis and data structuring skills in Python. It shows how raw company data can be transformed into a format that supports clearer analysis, trend detection, and visualization.

## Author

Evgeny
