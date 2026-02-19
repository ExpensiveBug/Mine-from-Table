## **Streamlit Mine Table**

### Description
This is a Project is an interactive, multi-page Streamlit dashboard designed to simplify the entire data preprocessing workflow from uploading raw datasets to cleaning, visualizing, and exporting refined data.

## Installation
pip install -r requirements.txt
---
## Run the App
streamlit run start.py
---

## Features
- Upload CSV and Excel files
- View dataset preview instantly
- Rename or drop columns
- Handle missing values using multiple strategies
- Visualize statistical summaries and data distributions
- Export cleaned data in multiple formats
- Dark-themed, user-friendly interface
---

## Application Workflow
1. Upload dataset
2. Preview data
3. Preprocess columns and handle missing values
4. Visualize statistics and distributions
5. Export the processed dataset
---

# Table of Contents
1. [Go to Preprocess Data](#preprocess-data)
2. [Go to Missing Value Handling](#missing-value-handling)
3. [Go to Data Visualization](#data-visualization)
4. [Go to Export Data](#export-data)
5. [Go to Supported File Formats](#supported-file-formats)
6. [Go to Example Dataset](#example-dataset)
7. [Go to Technologies Used](#technologies-used)


## Preprocess Data
### Column Operations
- **Rename Columns**  
  Select an existing column and assign a new name.
- **Drop Columns**  
  Remove unnecessary columns from the dataset.

  ### Missing Value Handling
Choose one of the following methods:
- Fill with **mean**
- Fill with **median**
- Drop rows containing missing values
- Fill with a custom value
Apply changes instantly with the **Apply Changes** button.
---

## Data Visualization
### Column Statistics
- Mean
- Median
- Minimum value
- Maximum value
- Count

### Missing Values & Duplicates
- Summary of missing values per column
- Duplicate row detection

### Data Distribution
- Histogram plots for selected numeric columns
- Interactive column selection
---

## Export Data
- Export cleaned dataset in **CSV** format
- Custom file name support
- One-click download
---
## Supported File Formats
- `.csv`
- `.xlsx`
---

## Example Dataset
The application includes a sample dataset to demonstrate:
- Column statistics
- Missing value handling
- Data visualization capabilities
---

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Streamlit (or Flask/Dash – update if needed)
- HTML / CSS
