# problem 1 : Web scraping tool
## Dependencies Required:
- requests: This library is used to make HTTP requests to the GitHub API.
```text
  pip install requests
```
- pandas: This library is used for data manipulation and saving data into CSV format.
```
  pip install pandas
```
- google.colab.files (optional - only for Colab usage):
```
from google.colab import files
```
## Steps to Run the Script
- Step 1: Install Python, Ensure Python is installed on your system
- Step 2: Install Required Dependencies
- Step 3: Obtain Your GitHub Personal Access Token
- Step 4: Run the Script
```
python web_scraper.py
```

# Problem 2: Automating a KPI Dashboard
## Dependencies Required:
- pandas: Used for handling and processing the data from the CSV files
- matplotlib: Used for creating visualizations like bar charts and pie charts.
```
pip install matplotlib
```
- fpdf2: Used to create the PDF report.
```
pip install fpdf2
```

## Steps to Run the Script
- Step 1: Install Python, Ensure Python is installed on your system
- Step 2: Install Required Dependencies
- Ensure the script files (users.csv and repositories.csv) are available in the same directory or provide the full path to these files.
- Run the Script:
```
python kpi_dashboard.py
```
