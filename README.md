## Data Science Practice with Python

This repository contains Python scripts showcasing various functionalities of the Pandas library for data manipulation and analysis.

**1. Exploring CSV and Excel data:**

* `pandas_basics.py` demonstrates:
    * Importing pandas library
    * Reading data from CSV and Excel files
    * Viewing data head, tail, and specific columns
    * Getting data types and column names
    * Selecting specific columns and rows
    * Checking data types of individual columns

**2. Reading data from URLs:**

* `pandas_url_data.py` demonstrates:
    * Reading data from a URL using pandas
    * Extracting specific tables from the webpage using `read_html`
    * Selecting and manipulating the desired data

**3. Saving data to CSV:**

* `pandas_url_data.py` also demonstrates:
    * Saving the selected data frame to a CSV file

**Prerequisites:**

* Python 3.x
* pandas library (`pip install pandas`)
* lxml library (`pip install lxml`) for URL data access

**Running the scripts:**

1. Clone this repository.
2. Open a terminal or command prompt and navigate to the repository directory.
3. Install required libraries: `pip install pandas lxml`
4. Run the scripts using: `python pandas_basics.py` or `python pandas_url_data.py`

**Note:**

* The script for reading data from URL requires the `lxml` library for parsing the HTML content.
* Replace `"https://raw.githubusercontent.com/datasciencedojo/datasets/master/titanic.csv"` with the actual URL if you want to use a different dataset.

This repository serves as a basic introduction to data manipulation and analysis using pandas. You can further explore and practice with various functionalities and techniques provided by the library.
