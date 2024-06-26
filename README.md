# Python Job Market Analysis

This project scrapes job postings for Python developers from the Djinni website and analyzes the most demanded technologies in the market.


## Table of contents
1. Installation
2. Usage
3. Contributing
4. License
## Installation
Before you start, ensure you have met the following requirements:

* You have installed Python 3.8 or later.
* You have installed the required Python libraries. You can install them using pip:## Usage

To use this project, follow these steps:

1. Run the scraping script to collect data about job vacancies:
   ```sh
   python scrapping/scrapper.py
This will create a CSV file named vacancies.csv with data about job vacancies.
1. Run the analysis script to analyze the data:
   ```sh
   python analysis/analysis.py

This will create a bar plot of the technologies found in the job vacancies and save it in the ‘plots’ directory.

## Contributing

Contributions to this project are welcome. If you have a feature request, bug report, or want to contribute to the code, please open an issue or submit a pull request.
