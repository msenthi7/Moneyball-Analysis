# Project 2-2

This Jupyter Notebook demonstrates a complete data analysis workflow involving **data wrangling**, **database operations**, and **data visualization**.  
The project is executed in Google Colab with integration to Google Drive for file access.

## Overview

The notebook covers:
- Connecting to and working with an SQLite database.
- Data wrangling and cleaning.
- Querying structured datasets.
- Preparing data for analysis.
- Visualizing results.

## Main Sections

### 1. Wrangling
- **Connecting to SQLite Database**: Uses `sqlite3` in Python to connect and query data.
- **Google Drive Integration**: Access files stored in Google Drive directly from Colab.
- **File Exploration**: Commands to list and verify dataset availability.

### 2. Data Processing
- Data cleaning and transformation.
- Filtering, sorting, and aggregating datasets.
- Handling missing values.

### 3. Analysis
- Executing SQL queries within Python.
- Joining tables to combine relevant data.

### 4. Visualization
- Creating plots to understand trends in the dataset.
- Using `matplotlib` and/or `seaborn` for graphical representation.

## Requirements

- Python 3.x
- Google Colab or Jupyter Notebook
- SQLite3
- Pandas
- Matplotlib
- Seaborn

Install dependencies (if running locally):
```bash
pip install pandas matplotlib seaborn
```

## How to Run

1. Open this notebook in Google Colab or Jupyter Notebook.
2. If using Google Colab:
   - Mount Google Drive using:
     ```python
     from google.colab import drive
     drive.mount('/content/drive')
     ```
3. Connect to the SQLite database file.
4. Execute the notebook cells step-by-step.

## Example Output

- SQL query results displayed as Pandas DataFrames.
- Graphical plots representing aggregated data.

## License

This project is open-source and available under the MIT License.
