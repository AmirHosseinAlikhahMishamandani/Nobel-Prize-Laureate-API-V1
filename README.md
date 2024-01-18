# Nobel Prize Laureate Data Processor

## Description
This repository contains a Python script that interfaces with the Nobel Prize API to fetch laureate data. It processes this data by concatenating the first and last names of the laureates, adding this as a new column, and saving the updated information into a CSV file. This script is useful for data analysis and research purposes, providing a clean and comprehensive dataset of Nobel Prize laureates.

## Getting Started

### Dependencies
- Python 3.x
- `requests` library
- Internet connection for API access

### Installing
- Clone the repository using `git clone [repository-url]`.
- Install required Python packages: `pip install requests`.

### Executing the program
- Run the script using Python: `python nobel_prize_data_processor.py`.
- The script will create a CSV file named `modified_nobel_prize_data.csv` in the current directory.

## How It Works
1. The script sends a GET request to the Nobel Prize API.
2. It reads the CSV data response and processes each row.
3. For each laureate, it concatenates their first and last names.
4. The script writes the processed data to a new CSV file with an added 'Full Name' column.

## Authors
[Your Name or GitHub Username]

## Acknowledgments
- Nobel Prize API for providing the data.
- Contributors and supporters of the project.
