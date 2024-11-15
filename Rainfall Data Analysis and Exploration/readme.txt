# Rainfall Data Cleaning and Analysis

## Project Overview

This academic project involves cleaning, preparing, and analyzing the dataset provided by Australian Government - the Bureau of Meteorology, which contains daily rainfall climate data between 2013 and 2023 in ABC city. The dataset includes columns for year, month, day, and rainfall (in mm). The data undergoes several cleaning steps to handle missing values, incorrect entries, and outliers before performing analysis on the trends and comparisons of rainfall across different years and months.

The analysis includes:
- Cleaning the dataset (handling missing, incorrect, and outlier values).
- Visualizing rainfall data for specific years.
- Comparing annual and monthly rainfall trends.
- Exploring the top and bottom rainfall years.
- Analyzing changes in average rainfall over the last decade (2013–2023).

**Technologies Used:**
- Python
- Pandas
- Matplotlib
- NumPy

## Project Structure

- **`rainfalldata/`**  
  - Contains the raw data file `Data.csv` (raw dataset for rainfall data).
  
- **`cleaned_version.csv`**  
  - The cleaned version of the dataset saved after data preparation steps.

- **`analysis.py`**  
  - Contains the full code for data cleaning, exploration, and visualizations.

## Steps to Run the Code

1. **Clone the repository**:

```bash
git clone https://github.com/yourusername/rainfall-data-analysis.git
cd rainfall-data-analysis

2.**Install dependencies**:
Ensure you have Python installed (preferably version 3.7 or later). You can install the necessary packages using pip:

bash
pip install pandas numpy matplotlib
Alternatively, you can create a requirements.txt and install dependencies:

bash
pip install -r requirements.txt

3. **Run the Analysis**:
Open analysis.py and run the code using any Python IDE or directly via the command line:

bash
python analysis.py
This script will load the data, clean it, handle missing or incorrect values, and then produce several visualizations to analyze rainfall patterns.

4. **View the cleaned dataset**:
After running the script, the cleaned dataset will be saved as cleaned_version.csv, which can be loaded for further analysis or shared with others.'''

##Final Output:
* The cleaned dataset is saved as cleaned_version.csv.
* The analysis is displayed as visual graphs and figures using Matplotlib.

##Conclusion

This project demonstrates how to clean and analyze climate data to derive meaningful insights. The cleaned dataset and visualizations offer a clear overview of rainfall patterns, including yearly comparisons, monthly trends, and long-term changes over the last decade.


